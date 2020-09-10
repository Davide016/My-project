The sh script that is in this folder is used to update any packages on Ubuntu or Debian based
distro like Linux Mint, Debian and Ubuntu itself ecc... . I hope you like the sh script.
This script was done in bash. 

To verify that the script just downloaded has the permissions to run, you have to go with the terminal to the directory where you downloaded it and give the command

```bash
ls -l
```

The command you just ran will give you output similar to this:

```bash
-rwxrwxr-x 1 davide davide 627 lug 24 14:06 ciao.sh
```

Instead if you want to see more easily if the script has execute permissions, press the right mouse button on the script sh just downloaded and go to the file properties and go to the permissions section and see if there are program execution permissions enabled. If the permissions are enabled, proceed with the execution of the script using the following command from the terminal:

```bash
./ciao.sh
```

and press enter and the script will run correctly. Before running it, enter the password as the commands to be executed by the script will be executed with the permissions of sudo. Remember that if you see the permissions disabled, you will need to proceed to enable them.

CAREFULLY REMEMBER: before running the script run the command:

```bash
sudo apt install -f
```

and hit enter. After the command is finished you will see if there are packages to update. If there are packages to upgrade, proceed with running the script to upgrade the system from the command line. 

This command will give you output similar to this:

```bash
Reading package list... Done
Dependency tree generation      
Read status information... Done
0 updated, 0 installed, 0 to be removed, and 10 not updated.
```

This script is distributed under the GNU GPL V.3 license. To see the license agreement click on the file called LICENSE.


