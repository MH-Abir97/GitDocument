# Git Document

Three Type of Area in Git 

- Working Directory or Work Space

 - Stagging Area

 - Local Repository
 
  Folder Directory
  
  ```
   $ pwd
  ```
  
  > Git Initilazition in Working Directory
  Entry Directory
  
  
 ``` $ mkdir
 ```
 
 ``` $ cd <file name>```
 
  Command :
   Default Directory File seen 
   
   ```$ ls -a  ```
   
  ```$ git config -global user.name "Abir-97" ```
  
  ``` $ git config -global user.email "abirkhan97@gmail.com" ```
  
  User Name & Email Seen
  
  ``` $ git config -global user.name ```
  
  ``` $ git config -global email.name ```
  
   Git Initialize
   
   ``` $ git init ```
   
   File Create
   
   ``` $ touch <FileName> ```
   
   Status check
   
   ``` $ git status ```
   
   ## Move to Stagging Area 
   
   
   ``` $ git add .  < all File Added Stagging Area or tracking > ```
   
   
   ``` $ git add <filename> ---Single file added ```
   
   
   Use  to discard changes in working directory
   
   
   ``` $ git restore <fileName> ```
   
   
   File or modified Data  unstage or non-tracking
   
   
   ``` git rm --cached <file>  ```
   
   > Local Repository
   
   
   Commit on uncommit File and Modified data in Local Repository
   
   Commit :
   
   
   ``` $ git commit -m "My First commit" ```
   
   Commit and Stagging
   
   ``` $ git commit add . && git commit -m "my first commit" or $ git commit -am "My First Commit" ```
   
   
   ### Uncommit
 
   Recent Commit Undo
 
   ``` $ git reset --soft HEAD^ ```
 
   Recent Commit undo or uncommit and Remove from Stagging Area 
   
   ``` $ git reset HEAD^ ```
    
   Go back to the last comment and uncommit & untraccking  in the staging area
   
   ``` $ git reset --hard HEAD^ ```
   
   Git History 
 
   ``` $ git log ```
 
   Specific  One Commit  Show
   
   ``` $ git log -oneline ```
 
  Back to The Previous Commit step to Step
 
 ``` $ git checkout <HEAD ID > ```
 
  Back to The Previous 
 
 ```
 $ git checkout master
 ```
 
 Local Repository Connected to Remote Repository
 
 Remote Repository Check
 ```
 $ git remote
 
 ```
 
 Connect Remote to Local
 
 ```
 $ git remote add origin <Remote Git Link>
 ```
 
 Origin define Gir Url link
 
 Git Clone 
 
 ```
 $ git clone <Git Remote Link>
 ```
   
 
  
  
  
 

