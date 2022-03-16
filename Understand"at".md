### Goal: Schedule a task for a future time.Make a task repeat at a specific time,periodically,every day,or every month

####  At Command:

Syntax is as follows:

$ at time date 

examples of the at command:
 - The control + D command will save the at job.The following task will be executed at 11.15 A.M.
   ```
   $ at 11.15 AM
   at > echo "Hello World" > $HOME/log.txt
   at > Control + D 
    ```   
 - All the jobs which are scheduled by the command at command can be listed using the 'atq' command.
  ```
  macP:~ chen$ atq
  1	Wed Mar 16 11:45:00 2022
  ```
 - To remove a specific job listed by the atq command, we can use the following command:
 ```
 $atrm job-id
 ```  
   
