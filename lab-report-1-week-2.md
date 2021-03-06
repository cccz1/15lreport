# Lab1

![Image](https://github.com/cccz1/15lreport/blob/main/task1-diagram.png?raw=true)

- Installing VScode
- Remotely Connecting
- Trying Some Commands
- Moving Files with scp
- Setting an SSH Key
- Optimizing Remote Running
## Installing VScode
1. download VScode from  [link](https://code.visualstudio.com/), then install it.
    ![Image](https://github.com/cccz1/15lreport/blob/main/Screenshot%202022-01-14%20101126.png?raw=true)
## Remotely Connecting
2. You are supposed to connect the server via your ieng6 account. to activate it, go to ITS dest to change your password. Then use the new password to log into the account under the `$ ssh youraccount` command.
    ![Image](https://github.com/cccz1/15lreport/blob/main/Screenshot%202022-01-14%20101330.png?raw=true)
## Trying Some Commands 
3. Try some commands on the server.<br />
`-ls`<br />
`-cd -`<br />
`-pwd`<br />
    ![Image](https://github.com/cccz1/15lreport/blob/main/Screenshot%202022-01-14%20101529.png?raw=true)
## Moving Files with scp
4. Then, use exit command to exit, and create a file on your local folder. Then use the `$ scp filename account` command to copy that file to the server. You may be asked to type in your password again.
![image](https://github.com/cccz1/15lreport/blob/main/Screenshot%202022-01-14%20101624.png?raw=true)
## Setting an SSH Key
5. Use `$ ssh-keygen` command to set up the `ssh` key to avoid typing password every time you use the scp command. This saves you a lot of time.
    At this time, the `ssh-keygen` command has already been set up, and I don't have a screenshot for this at the time I set things up, so unfortunately, the screenshot cannot be provided.
    ![image](https://github.com/cccz1/15lreport/blob/main/Screenshot%202022-01-31%20174657.png?raw=true)
## Optimizing Remote Running
6. Use `;` to seperate the tasks, so that you can operate a multiple task command in one command line.  Us commandline argument such as `ls` locally so that I can avoid logging into the remote server to call these command again, saves time.
![Image](https://github.com/cccz1/15lreport/blob/main/Screenshot%202022-01-28%20152910.png?raw=true)