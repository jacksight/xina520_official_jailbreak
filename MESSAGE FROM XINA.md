# **This jailbreak is made by the developer @xina520.** 

Please do not harass or bombard the developer's Twitter. Don't go asking or harassing him about supporting more iOS versions or devices. Don't go asking or harassing him to fix issues that you encounter. He made a jailbreak for A12+ devices running iOS 15.0 up to 15.1.1 and we should be grateful for that.

# **Warning!**

XinaA15 is a in-development and public beta jailbreak. This jailbreak is **NOT** meant for normal public use. Please use this with precaution.
- [Device Compatibility List](https://github.com/NotDarkn/XinaA15/wiki/Compatibility)
- [Warnings About XinaA15](https://github.com/NotDarkn/XinaA15/wiki/Warnings)

# **Currently supported:**

XinaA15 currently support (or include) many of the following:
- Sileo, Saily, etc
- Built-in SSH, Tweak injection, etc
- libsubstitiute, libhooker, etc
- Decent-enough looking UI with options
- Easy installation, removal, updating, etc
- and much more.

# To Developers
### Supported Environments

XinaA15 is currently compatible with all of the development environments you currently use.

Currently, the debug server fully supports the debugging of additional processes (you don't need to do anything.)
***
### **Development Daemons**

- `launchdhook` → (can't be ended) function hook launch
- `jailbreak_safe` → (non ending) function can be started again without exploiting vulnerabilities
- `jailbreakd` → (cannot be ended) Function signature and all signing permission related operations
- `jailbreakd_cmd` → this was recently added and Xina520 has not reported on what it does.
***
### Development Information

There's no need to change **theos** or anything else, but what you may need to change is the relevant path in your code (the path in the deb package does not need to be changed, and nothing else needs to be changed)

- Full support for `make install`
- Full support for `make uninstall`
- Full support for `make do`
***
### Installing iOSOpenDev

For the normal use and installation of iOSOpenDev, no changes are required.

1. Compile the log. 

During the compilation process, the console will display the current log. Please ignore the following:

`ldid: Unknown header magic`

`Are you sure that is a Mach-O?`

`ldid: operator(): No such file or directory`

2. After that, do the following:

`make uninstall`

`make install`

# **Development Directories**

### Jailbreak Directory
- `/var/jb`

Ths is XinaA15's equivalent to root, however it's in `/var`, as this directory supports external read/write permissions, which can be used for data for tweaks.
***
### **Font Directory**
- `/var/jb/Library/Fonts`
 
The fonts in this directory are changeable if requested by the user.
***
### **Guardian Directory**
- `/var/jb/Library/LaunchDaemons`
***
### **For more directories, check here:**
- `/var/jb/Library/`

# SSH on XinaA15
In XinaA15, we support connecting to your phone with SSH as long as you're jailbroken! Below is how to connect through SSH or reset your SSH password.

### How to connect through SSH:
**1.** Configure the SSH to be connected to the port: `22` (this should be 22 by default)

**2.** After that, input: `ssh root@(your local device IP)` (example: `ssh root@192.168.1.2`)

**3.** If asked for a SSH password, input the default password: `alpine`

### How to temporarily reset the SSH password:
**1.** Input the following command and press enter: `ssh-copy-id -i $HOME/.ssh/id_ rsa` 

**2.** After that, input: `ssh root@(your local device IP)` (example: `ssh root@192.168.1.2`)

# **Extra**

If your storage in iCloud is full, the app signature will become invalid after the space has become full. This could also possibly cause some other problems. The cause for why this even happens is unknown, however it is to be fixed.

It is also highly recommened to not update all of the 35 packages in Sileo. While in `1.1.3.6` and `1.1.4` it won't cause too many issues, it is absolutely recommended to not do this in `1.1.5` or higher. Planned to be fixed.

If Xina has more to say or update in his message, this .txt will be updated.

If you have any bugs, please report in [GitHub Issues](https://github.com/jacksight/xina520_official_jailbreak/issues) or join the [XinaA15 Discord Server](https://discord.gg/xina-a15)
