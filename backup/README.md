##Git-Bash-ML1
Today learned Bash commands 
mkdir (for making directory).
cd (for moving into directory).
cd .. (formoving back from the current directory).
touch filename.file-extension (for creating file in the directory).
cat filename.extension (for reading the text from the file).
echo "anything that you want to add in the file" >> filename, (this will append the given text in the comas in to the mentioned file in the end).
tail filenme.extension (this will print the last 5 text from the file).
bash -i script.sh (This command is used for running the script file)
##Git Commands 
Today learned Git commands
git clone URL (this will clone your repo with git).
some initial git commands step for pushing the repo's from bash terminal
1 git config --global user.email "write your email"
2 git config --global user.name "write name"
3 git init
4 git add readme.md 
5 git commit -m "first commit"
6 git branch -M main
7 git remotre add origin URL
8 git push -U origin main
##Commands used in task for extracting users and erros from the log files 
names=$(grep -roP "User=\K\w+" *) (names is a variable which will stores all the user names from different log files present in the current diractory).
touch Name.txt (For storing the username in to a text file).
printf "%s\n" $names >> Name.txt (this command will save the names in sperate lines).
errors=$(grep -r "\[ERROR]" *) (THis will save all the error with user name in errors varible).
touch Error.txt (create file for saving the error details).
printf "%s\n" "$errors" >> Error.txt (Saving all the error details from variable to Error text file).
## Task Commands Terminal Basics 
1 cd path then ls -a (this will print all hidden folders and sub-flders)
2 mkdir Projects, cd Projects, touch README.md, echo "My Projects" >> README.md
3 chmod 700 script.sh (why 7, 4 is a permission used for read only, 2 is a permission used for only write while 1 is a permission used only execute, when addup to these 3 number you will get 7 means that the owner has read, write and execute permission).
4 


