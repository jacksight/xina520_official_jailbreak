# **This jailbreak is made by the developer @xina520.** 

Please do not harass or bombard the developer's Twitter. Do not go asking or harassing him about adding more iOS versions or devices, or to fix issues that you encounter. He made a jailbreak for A12+ devices running iOS 15.0 up to 15.1 and we should be grateful for that.

# **Warning!**

XinaA15 is a in-development and public beta jailbreak. This jailbreak is **NOT** meant for normal public use. Please use this with precaution.
- [Warnings about XinaA15](https://github.com/NotDarkn/XinaA15/blob/main/WARNINGS.md)
- [Device/iOS Compatibility List](https://github.com/NotDarkn/XinaA15/blob/main/SUPPORTED.md)

# **Currently supported:**

XinaA15 currently supports many of the following:
- Sileo
- Built-in SSH 
- libsubstitiute
- libhooker
- Proscurus, BigBoss, and more repos
- Tweak injection
- etc

# **Supported development environments**

XinaA15 is currently compatible with all of the development environments you currently use.

Currently, the debug server fully supports the debugging of additional processes (you don't need to do anything.)

# **Developers!**

There's no need to change **theos** or anything else, but what you may need to change is the relevant path in your code (the path in the deb package does not need to be changed, and nothing else needs to be changed)

- Full support for make install
- Full support for make uninstall
- Full support for make do

**Installaton of iOSOpendev:**

For the normal use and installation of iOSOpendev, no changes are required.

1. Compile the log. 

During the compilation process, the console will display the current log. Please ignore the following:

`Idid: Unknown header magic`

`Are you sure that is a Mach-O?`

`Idid: operator(): No such file or directory`

2. After that, do the following:

`make uninstall`

`make install`

# **Jailbreak Directory**
/var/jb
Equivalent to the previous root (this directory supports third-party APP read/write permissions, which can be used for process data interaction)

# **Font Directory**
/var/jb/Library/Fonts (fonts can be changed)

# **Guardian Directory**
/var/jb/Library/LaunchDaemons

# **For more directories, check here:**
/var/jb/Library/

# **About my daemons**

launchdhook (can't be ended) function hook launch

jailbreak_ safe (non ending) function can be started again without exploiting vulnerabilities

jailbreakd (cannot be ended) Function signature and all signing permission related operations

# **Extra**

If your storage in iCloud is full, the app signature will become invalid after the space has become full. This could also possibly cause some other problems. The cause for why this even happens is unknown, however it is to be fixed.

It is also highly recommened to not update all of the 35 packages in Sileo. While in `1.1.3.6` and `1.1.4` it won't cause too many issues, it is absolutely recommended to not do this in `1.1.5` or higher. Planned to be fixed.

If Xina has more to say or update in his message, this .txt will be updated.

If you have any bugs, please report in [GitHub Issues](https://github.com/jacksight/xina520_official_jailbreak/issues) or join the [XinaA15 Discord Server](https://discord.gg/xina-a15)
