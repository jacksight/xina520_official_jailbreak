# How to connect to your XinaA15 device through SSH

**1.** Configure the SSH to be connected to the port: `22` (this should be 22 by default)

**2.** If asked for a SSH password, input the default password: `alpine`

**3.** After that, input: `ssh root@(your local device IP)`

# If you need to repair your SSH password temporarily:

**1.** Input the following command and press enter: `ssh-copy-id -i $HOME/.ssh/id_ rsa` 

**2.** After that, input: `ssh root@(your local device IP)`
