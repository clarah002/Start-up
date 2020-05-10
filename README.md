# Start-up
starting to learn how to use Github

Add new repository/start a new project
name of new project/repository
add read me and licence files

CONFIGURATIONS
open terminal, - git config --global user.name "username"
                  git config --global user.email "email"
                   git config --list (this will list user name and email configured)
                    
                    or
  ls -al (list all files use gedit to open gitconfig file)
  gedit gitconfig (all configured detail will be listed name and email )
  
  CLONE
  
  make the directory that will contain all files 
  mkdir git-workspace
  on browser click  on clone/download copy the url
  on terminal - git clone (paste the url )
                cd git-workspace 
                ls git-workspace (it will be contain readme and lisence files)
                
 TO CREATE FILE
 in terminal - touch fileName(welcome.html)( create a file in git-workspace directory)
                git add welcome.html (this add the file to git)
                
  COMMIT
  in terminal - git commit -m "write comment " (filename) welcome.html 
  
  PUSH 
  git push -u origin master 
  username
  password
  (all  files will be pushed into git repository)
