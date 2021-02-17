# meca-toronto-upgrade

## Instructions
Hi Brother Larry, good that you succeeded in downloading these files.  Now, the next step is to copy all the MECA Toronto files and put inside any folder of your choice in your computer, which I would call the "deployment folder", and then make a note of that folder because every instruction you would be following, would be based on that folder or directory. 

### Note that I would be writing all commands in between these characters "<>", don't include the characters when running the commands

## Upload Instructions
- So make sure that the code that you are sending, has not been minified, which means I can be able to work on it.
- Copy the code to the deployment folder and when done, open the windows command prompt or if you are using the Mac computer, open the terminal and navigate to that deployment folder.
* To open the command prompt in winodows, type "CMD" in the search box next to the windows button at the bottom right corner of your windows 10 operating system.
* To navigate to the folder of your choice (which is after you must have created the folder), in the command prompt window, type: <cd ...>  and the dots represent the path to the deployment folder, and then press enter.

- When the command prompt shows you that you are now in that folder, then type the following command and then press enter.
<git status>  and if you see all the files you have added written in red, it means that those are the files that would be sent at the end.

- And if the above command doesn't give you an error, then run the next command:
<git add .>   and if after this, you type the command <git status> and you see all the files listed in green, know that you are okay and it is ready to receive the comments.

- Next, you have to add a comment so type the following command:
<git commit -m "Sending the original code to Roland">  and then press enter.  If you now type the command <git status>, it would tell you something like "Upto date with branch master, Nothing to commit, the repository is clean..."  which means you are now ready to send the files.

- But before sending, type the following command:
<git pull origin master> This should bring in any updates, from the remote repository, else it would not allow you to send. 

- Now send the files with the following command...
<git push origin master>   And it would ask for your user name and password, enter them and press enter and if you see it do a number of things and counts from 1% to 100%, then the files were sent.

