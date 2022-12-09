**This file is made by @xina520, grammar corrected by discord user "alucard#2478"**

**What developers need to know**

After you get the tool, you'll need to sign the ipa or use Trollstore to install it to your device, so you can open the app.

**Supported development environments**

Compatible with all development environments you currently use.
Currently, the debugserver fully supports the debugging of additional processes (you don't need to do anything.)

**Environment repair**

If your environment is damaged, you can restart your phone, turn on the "rebuild jailbreak rnvironment" switch, and then turn on the jailbreak.

If there is a Sileo 522 error, try to repair the sileo language. If it's invalid for you, try to restore phone settings.

**Connecting to the device**

Configure the complete ssh port 22

Configure SSH password free root password on the console (default: alpine) 

Unable to repair password temporarily

`ssh-copy-id -i $HOME/.ssh/id_ rsa` 

Pub root @ your ip

**Warning!**

The current test version only supports 15.0-15.1.1 A12-A15-M1. 
Rootless jailbreak supports some tweaks. Some unsupported tweaks need to be updated by the plug-in author to support rootless environments. This version integrates Sileo, TrollStore, ssh, libsubstitute, Libhooker, Procursus, Bigboss, etc.

If your storage in iCloud is full, the permanent signature will become invalid after the space is restarted. It may also lead to some other problems. The current cause is unknown (to be fixed.)

There's no need to change the theos or change anything, but what you may need to change is the relevant path in your code (the path in the deb package does not need to be changed, and nothing needs to be changed)

Full support for make install
Full support for make uninstalll
Full support for make do

For the normal use and installation of iOSOpendev, no changes are required.

Compile the log. 

During the compilation process, the console will display the current log. Please ignore it.

If the console displays as follows:

ldid: Unknown header magic

Are you sure that is a Mach-O?

ldid: operator(): No such file or directory

make uninstall

make installl

**Jailbreak Directory**

/var/jb
Equivalent to the previous root (this directory supports third-party APP read/write permissions, which can be used for process data interaction)

**Font Directory**

/Var/jb/Library/Fonts (fonts can be changed)

**Guardian Directory**

/var/jb/Library/LaunchDaemons

**Please check other directories**

/var/jb/Library/

**About my daemons**

Launchdhook (can't be ended) function hook launch

jailbreak_ safe (non ending) function can be started again without exploiting vulnerabilities

Jailbreakd (cannot be ended) Function signature and all signing permission related operations


### **BUGS**
White icon of known third-party system process (will be solved in future update)


If I have more to say, I will update here

Test available plug-ins: (Continuously updating)



## Version 1.1.3.6 changelog: 
 
* Fixing the problem of usb stuck

* Fix my program sharing send file problem

* Fix 1.1.3.5 Applist does not work properly

* Fix the problem of translation failure of the system

* Fix some possible restart problems

* Fix testlight failing to update

* Fix the problem of third-party programs failing to inject

To install the new version, restart the phone and select "reinstall the jailbreak environment" and jailbreak
