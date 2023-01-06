# **This jailbreak is made by the developer @xina520.** 

# **Warning!**
XinaA15 is a in-development jailbreak. This jailbreak is **NOT** meant for normal public use. Please use this with precaution.
- [All warnings of XinaA15](https://github.com/NotDarkn/XinaA15/blob/main/WARNINGS.md)
- [Supported devices/iOS](https://github.com/NotDarkn/XinaA15/blob/main/SUPPORTED.md)

# **Currently supported:**
XinaA15 currently supports many of the following:
- Sileo
- Built-in SSH 
- libsubstitiute
- libhooker
- Procursus repo
- BigBoss repo
- Tweak injection
- and etc.

# **Supported development environments**

XinaA15 is currently compatible with all of the development environments you currently use.

Currently, the debug server fully supports the debugging of additional processes (you don't need to do anything.)

# **Developers!**

There's no need to change the theos or change anything, but what you may need to change is the relevant path in your code (the path in the deb package does not need to be changed, and nothing needs to be changed)

- Full support for make install
- Full support for make uninstalll
- Full support for make do

**Installaton of iOSOpendev:**
For the normal use and installation of iOSOpendev, no changes are required.

1. Compile the log. 

During the compilation process, the console will display the current log. Please ignore the following:

`ldid: Unknown header magic`

`Are you sure that is a Mach-O?`

`ldid: operator(): No such file or directory`

2. After that, do the following:

- make uninstall

- make installl

# **Jailbreak Directory**
/var/jb
Equivalent to the previous root (this directory supports third-party APP read/write permissions, which can be used for process data interaction)

# **Font Directory**
/Var/jb/Library/Fonts (fonts can be changed)

# **Guardian Directory**
/var/jb/Library/LaunchDaemons

# **For more directories, check here:**
/var/jb/Library/

# **About my daemons**

Launchdhook (can't be ended) function hook launch

jailbreak_ safe (non ending) function can be started again without exploiting vulnerabilities

Jailbreakd (cannot be ended) Function signature and all signing permission related operations

# **Extra**

If your storage in iCloud is full, the permanent signature will become invalid after the space has become full. This could also possibly cause some other problems. The cause for why this even happens is unknown, however it is to be fixed.

It is also recommended to not update all of the 35 packages inside of XinaA15, while you can do this in 1.1.3.6 and 1.1.4, you should definitely not do this in 1.1.5. The other reason also being because the majority of those 35 packages are yet to be updated for rootless jailbreaks like XinaA15. Currently waiting for the developers to fix the issue.

If Xina has more to say or update in his message, I will update this .txt.

If you have any bugs, please report to either the official XinaA15 GitHub or join their Discord.
