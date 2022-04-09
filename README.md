# Linux-Assignment-QAAE

1. First I have brought/created a free tier AWS Linux server using AWS console and connected through following 
command:
   $ ssh -i "qa-2201-key-pair.pem" ec2-user@ec2-34-226-210-250.compute-1.amazonaws.com
2. nano already installed in the Linux. Confirmed by following command:
   [ec2-user@ip-172-31-23-17 ~]$ nano --version
3. git is not installed in Linux server. git is installed by following command:
   [ec2-user@ip-172-31-23-17 ~]$ sudo yum install git
4. git version is checked by the command
   [ec2-user@ip-172-31-23-17 ~]$ git --version
   The output is screen captured and uploaded as "1.Git-version"
5. QAAEB2201 Github repo is cloned by the following command under user directory and confirmed by executing
"ls" command:
   [ec2-user@ip-172-31-23-17 ~]$ git clone https://github.com/Jahidul2543/QAAEB2201.git
   [ec2-user@ip-172-31-23-17 ~]$ ls
   QAAEB2201
   Screen is captured and uploaded as "2.Clone-dir"
6. Under user directory one directory named "app" is created. Then copied all file and folders from cloned repo 
QAAEB2201 into app directory.   
   [ec2-user@ip-172-31-23-17 ~]$ mkdir app
   [ec2-user@ip-172-31-23-17 ~]$ cp -r QAAEB2201/* app
   [ec2-user@ip-172-31-23-17 ~]$ ls QAAEB2201/
   cleanup_script.sh  MyApp  output.txt  WorkList.txt
   [ec2-user@ip-172-31-23-17 ~]$ ls app/
   cleanup_script.sh  MyApp  output.txt  WorkList.txt
7. Screen capture is as Evidence of previous work of serial number 6 and uploaded as "3.Content-app".
8. Few more commands are practiced on the server.