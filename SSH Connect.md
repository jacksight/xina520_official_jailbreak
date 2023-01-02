# Quick Note:
**I have never used SSH before.** The majority of text here was copied & pasted from **"MSG from Xina.md"** and then community fixed by XinaA15 users such as **"The Bot Guy"** (roeegh#3643).

# How to connect to your XinaA15 device through SSH

Configure the SSH to be connected to the port: `22` (this should be 22 by default)

If asked for a SSH password, input the default password: `alpine`

After that, input: `ssh root@(your local device IP)`

# If you need to repair your SSH password temporarily:

Input the following command and press enter: `ssh-copy-id -i $HOME/.ssh/id_ rsa` 

After that, input: `ssh root@(your local device IP)`
