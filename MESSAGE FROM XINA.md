# **This jailbreak is made by the developer @xina520.** 
# Most of the grammar was corrected by Discord user: "alucard#2478" (Thanks alucard for making my job easier!)

**Warning!**

XinaA15 is a in-development jailbreak. This jailbreak is **NOT** meant for normal public use. Please use this with precaution.
- [All warnings of XinaA15](https://github.com/NotDarkn/XinaA15/blob/main/WARNINGS.md)
- [Supported devices/iOS](https://github.com/NotDarkn/XinaA15/blob/main/SUPPORTED.md)

**Currently supported:**
XinaA15 currently supports many of the following:
- Sileo
- Built-in SSH 
- libsubstitiute
- libhooker
- Procursus repo
- BigBoss repo
- Tweak injection
- and etc.

**Updating and Error Fixing**

If your jailbreak is damaged in any way possible, you can restart your phone, turn on the "rebuild jailbreak environment" toggle, and then press "openJailbreak" to re-jailbreak.

If you encounter a Sileo 522 error, you can try clearing Sileo's cache to fix it. If it's still erroring however, try resetting your iPhone/iPad settings.

**Supported development environments**

**Note from Darkn:** Here on out, it gets kind of confusing on what Xina is trying to say or explain, even after multiple grammar and spelling corrections. For now, if you find any issues, please tell me!

XinaA15 is currently compatible with all of the development environments you currently use.

Currently, the debug server fully supports the debugging of additional processes (you don't need to do anything.)

**Developers!**

There's no need to change the theos or change anything, but what you may need to change is the relevant path in your code (the path in the deb package does not need to be changed, and nothing needs to be changed)

- Full support for make install
- Full support for make uninstalll
- Full support for make do

**Installaton of iOSOpendev:**
For the normal use and installation of iOSOpendev, no changes are required.

1. Compile the log. 

During the compilation process, the console will display the current log. Please ignore it:

ldid: Unknown header magic

Are you sure that is a Mach-O?

ldid: operator(): No such file or directory

2. After that, do the following:

- make uninstall

- make installl

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

### **Extra**

If your storage in iCloud is full, the permanent signature will become invalid after the space has become full. This could also possibly cause some other problems. The cause for why this even happens is unknown, however it is to be fixed.

If Xina has more to say or update in his message, I will update this .txt.

If you have any bugs, please report to either the official XinaA15 GitHub or join their Discord.
