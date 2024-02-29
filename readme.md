# Surge激活方法

1. 点击star<br>
      ![Star.png](/png/Star.png)  
   
2. 检查权限及其他设置<br>
      打开设置--隐私与安全性<br>
         1. 授予终端完全磁盘访问权限<br>
            ![完全磁盘访问权限.png](/png/完全磁盘访问权限.png)  
         2. 授予终端App管理权限<br>
            ![App管理权限.png](/png/App管理权限.png)  
         3. 授予终端开发者权限<br>
            ![开发者权限.png](/png/开发者权限.png)  
         4. 将安全性改为任意来源<br>
            在终端中输入 sudo spctl --master-disabl<br>
            ![安全性.png](/png/安全性.png)  
         5. 将Surge安装到/Applications中<br>
            ![安装到Applications中.png](/png/安装到Applications中.png)
            ![Surge.png](/png/Surge.png)  
         6. 关闭Surge<br>
            ![关闭.png](/png/关闭.png)
   
4. 下载整个仓库<br>
      小白不知道点哪里下载整个仓库？[点我下载](https://github.com/QiuChenlyOpenSource/InjectLib/archive/refs/heads/main.zip)<br>
   
5. 下载后一般会自动解压，如没有自动解压请手动解压<br>
      ![双击原神启动.png](/png/双击原神启动.png) 
   
6. 双击 原神_启动.command 后，然后输入电脑的登录密码授予脚本权限<br>
      ![原神启动.png](/png/原神启动.png)  
   
7. 输入 “y” 执行注入操作<br>
      ![注入.png](/png/注入.png)  

8. 出现“进程已完成”即可关闭终端<br>
      ![关闭终端.png](/png/关闭终端.png) 

9. 大功告成<br>
      ![Surge激活.png](/png/Surge激活.png)

# 重点
部分可能会出现这个报错，目前无法解决，如果遇到说明你运气极差，只能找使用正常的人要一个注入后的“Helper”文件
        
      >
      FBundleVersion) does not exist
      2023-10-21 14:24:17.105 defaults[957:15054] 
      The domain/default pair of (/Applications/BAInstaller.app/Contents/Info.plist, CFBundleShortVersionString) does not exist
      2023-10-21 14:24:19.537 defaults[1042:15406] 
      The domain/default pair of (/Applications/eMuleTorrent.app/Contents/Info.plist, CFBundleVersion) does not exist
      [🤔] [Surge] - [5.4.0] - [com.nssurge.surge-mac]是受支持的版本，是否需要注入？y/n(默认n)
      y      
      开始注入App: com.nssurge.surge-mac


      ====================
      2023.2.26 秋城落叶修改版
      感谢insert_dylib的开源人员！仓库地址：https://github.com/Tyilo/insert_dylib
      ====================

      /Applications/Surge.app/Contents/Frameworks/Bugsnag.framework/Versions/A/Bugsnag 目标文件已经存在. 要重写他吗? [y/n] y
      这是一个FAT格式二进制,携带 2 个架构的代码(Intel/Apple Silicon ARM64).
      发现代码加载签名: LC_CODE_SIGNATURE load command. 要自动删掉吗? [y/n] y
      发现代码加载签名: LC_CODE_SIGNATURE load command. 要自动删掉吗? [y/n] y
      添加 LC_LOAD_DYLIB 指令到通用架构, 应用程序：/Applications/Surge.app/Contents/Frameworks/Bugsnag.framework/Versions/A/Bugsnag。
      Need Deep Sign.
      开始签名...
      /Library/LaunchDaemons/com.nssurge.surge-mac.helper.plist: Operation now in progress
      No matching processes were found
      感谢QQ 302****398 用户无偿提供授权信息。
      大胆！检测到你在用盗版软件，这可能会危害你的设备！还可能会导致你被有关监管部门或工业和信息化委员会上门约谈，请慎重考虑是否决定使用盗版！
      正在定位你的Mac物理地址...GPS定位中...你跑不掉了! 即将联系Surge开发者发送你的Mac所有信息，你即将被留存侵权数字证据，束手就擒！
      定位你的Mac物理地址完成，正在向国家安全局特工发送你的逮捕许可...
      起始点在 145313, 准备修改Helper文件。
      53+0 records in
      53+0 records out
      53 bytes transferred in 0.000308 secs (172057 bytes/sec)
      280+0 records in
      280+0 records out
      280 bytes transferred in 0.001735 secs (161386 bytes/sec)
      起始点在 358213, 准备修改Helper文件。
      53+0 records in
      53+0 records out
      53 bytes transferred in 0.000319 secs (166142 bytes/sec)
      280+0 records in
      280+0 records out
      280 bytes transferred in 0.001537 secs (182191 bytes/sec)
      下发逮捕许可完成,即将有人来查你的水表，你别急...海内存知己,天涯若比邻.正在黑进你的Mac,目前已成功骗取到用户root密码.
      /Applications/Surge.app/Contents/Library/LaunchServices/com.nssurge.surge-mac.helper: replacing existing signature
      /Applications/Surge.app/Contents/Library/LaunchServices/com.nssurge.surge-mac.helper: a required plist file or resource is malformed
      /Applications/Surge.app: replacing existing signature
      恭喜你！你的Mac已经被我植入了后门程序,现在即将结束整个进程，特工已经在对面楼中布下天罗地网，请主动自首争取宽大处理(虽然宽大不了几天)，记得下辈子不要用盗版软件🙏。
      Surge.app/Contents/Library/LaunchServices/com.nssurge.surge-mac.helper: a required plist file or resource is malformed
      
       
#helper文件所在路径  /Applications/Surge.app/Contents/Library/LaunchServices<br> 
      把里面的文件删了，换成使用正常的helper文件即可<br>
 # ARM芯片如果拉了最新的库，请务必使用最新版本的Surge，否则可能会有问题

#Surge Mac 助手程序（Helper）异常处理方式

如果 Surge Mac 助手程序（Helper）异常，会导致无法设置系统代理和无法开启增强模式。（使用 CleanMyMac 或其他清理软件强行清理可能导致该问题）

请参照以下步骤修复：

打开 Surge Mac 的设置界面，选择高级，选择移除助手程序（Remove Helper）。
输入你的系统密码。
点击打开终端（Open Terminal）。
在终端窗口处再次输入系统密码并回车。
重启电脑。
打开 Surge，尝试勾选设置为系统代理，输入系统密码重新安装助手程序。
如果依然不正常工作，且之前有使用过某些清理软件禁用 helper，请尝试执行

```bash
sudo /bin/launchctl load -w /Library/LaunchDaemons/com.nssurge.surge-mac.helper.plist
```
由于 macOS 是开发性系统，十分复杂，如果仍然不能正常工作，可能需要尝试重置整个系统。
