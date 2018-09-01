## App Systemizer (Terminal Emulator)
[More info and details in the XDA Thread](https://forum.xda-developers.com/apps/magisk/module-terminal-app-systemizer-ui-t3585851)

 Systemless地系统化app!
 使用终端模拟器.
 输入这个命令,然后选择你想要系统化的app.

	systemize
	
 你会看到一个已安装应用的列表
 重启以应用更改

## 遇到错误?
 到主菜单输入 `logs`, 这将上传模块的日志文件并生成链接. 发送它们 :)
 另外, 发送 `/cache/terminal_debloater-verbose.log` 到 XDA . 我会检查它的问题，然后试着解决它.

## 变更日志

### v14.1
* Update module template
### v14
* 添加 SELinux 选项使app检测更加迅速
* 使 "输入标签" 选项更快和更有效
* 将apk命名为它的父文件夹
* 其他改进

### 由于时间关系,不继续翻译旧版日志

### v13.5.1
* Fix app detection
### v13.5
* Fix errors when detecting $MOUNTPOINT free space
* Misc improvements
### v13.4.1
* Faster app loading (noticeable) when in ADB
* Improve xml file generated
* Misc improvements
### v13.3.1
* Fix systemizing glitches
* Misc improvements
### v13.3
* Fixed generating permissions
* Misc improvements
### v13.2
* Systemized app listing looks better and much more readable :3
* Misc improvements
### v13.1
* Add -l option to list systemized apps
* Apps doesn't get refreshed if you go back to menu
* Add "Refresh list" option in app list menu
* Misc improvements
### v13
* Add -a option to directly systemize a given package name
* Add -d option to directly systemize a given apk
* Automatically disable ANSI codes (the colors) when in ADB shell
* Add help message
* Misc
### v12.2
* Fixed quirks when listing app names
### v12.1
* Fixed stuff related to busybox alias
### v12
* Add Back to menu option
* Logs can now be uploaded by entering `logs`
* Other listed menus now have multiple option.
* Misc improvements XD

