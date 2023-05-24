# Linux-editing-working-with-files


## Setup:

run these commands before you start the lab:
- sudo mkdir -p  ~/mydir/mydir2
- sudo touch  ~/mydir/mydir2/yourname.txt
- cp /var/log/anaconda/syslog  ~/mydir/securecopy.txt 

## Tasks:

- cksum securecopy.txt and save the output as screen shot.
- open  ~/mydir/securecopy.txt with nano OR vim editor and replace all "root" keywords with yourname and exit the nano.
- again cksum securecopy.txt and save the output as screen shot and write your observation.
- use the find command to find yourname.txt in your environment and save the output as screen shot.
- Use man page with the "useradd" command and save the output in "useradd-man.txt" using what you have learned in "stdin/stdout" lesson, then grep the word "password" from the "useradd-man.txt" you have created and take a screen shot for the grep output.

## Additional Challenge:

- use the diff command on /var/log/anaconda/syslog and ~/mydir/securecopy.txt  file and save the output as screen shot

## Submission:

- After finishing the task take screen shot of the all Tasks.
- Then upload the pictures to the forked repo and then create a pull request.

----------------------------------------------------------------

