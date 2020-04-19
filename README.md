# Win to hack

## Create an infiltration environment based on windows win to go

*The system was modified based on Fireeye ’s Commando VM, optimized for win to go support, and modified and transplanted some software packages*

*该系统基于火眼公司的Commando VM加以修改，对win to go的支持进行了优化，并对一些软件包进行了修改和移植*

*注意：下载链接为网盘下载，不支持迅雷等多线程下载，使用普通浏览器下载，推荐使用谷歌。*

### 安装教程

#### 准备的工具：

*使用我打包好的系统：*
*  一台装有Windows系统的电脑（电脑至少保持有40GB的空余存储）
* 一个空的硬盘或U盘（最好是固态，U盘选择3.1或3.0的USB接口，不可使用2.0接口，速度太慢，随身携带自行购买硬盘盒等工具），至少128G！！

*自己配置环境：*
* 一台装有Windows系统的电脑（系统安装有VMware workstation虚拟机）
[此处下载](http://pgl888999.asuscomm.com:888/index.php/s/7TRbLdMx8mS0U7t)
* 一个空的硬盘或U盘（最好是固态，U盘选择3.1或3.0的USB接口，不可使用2.0接口，速度太慢，随身携带自行购买硬盘盒等工具）
* 一个Windows系统(Windows 10 1803, 1809, 1903 或者 1909)，至少128G！！
* 自备一架稳定的全局代理梯子，最好美国线路，在路由器全局代理，一定要有支持使用梯子的路由。

[下载链接](http://pgl888999.asuscomm.com:888/index.php/s/ZJxJPC9xxUDdCLw)

#### 安装步骤：

*使用我打包好的系统：*

1. 下载系统备份镜像。[下载链接](http://pgl888999.asuscomm.com:888/index.php/s/EOiSmS79G3KtZAc)
2. 下载还原工具。[下载链接](http://pgl888999.asuscomm.com:888/index.php/s/qEPqAnvJk09Yh2J)
3. 将还原工具解压，进入文件夹找到“Backupper.exe”，点击运行。
4. 还原到安装磁盘上。[还原教程](https://www.disktool.cn/backup/help/disk-restore.html)

*自己配置环境：*
1. 打开虚拟机-->创建虚拟机

![photo1](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19225101_LI.md.jpg)

2. 选择自定义-->下一步

![photo2](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19225101_LI.md.jpg)

3. 默认硬件兼容性-->下一步

![photo3](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19225101_LI.md.jpg)

4. 选择镜像文件(Windows 10 1803, 1809, 1903 或者 1909)-->下一步

![photo4](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19232647_LI.md.jpg)

5.密匙随意，下一步

![photo5](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19225837_LI.md.jpg)

6.命名随意，位置默认即可，下一步

![photo6](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19225856_LI.md.jpg)

7.根据自己的电脑选择，这里一般选择UEFI，因为现在大多数主板都支持UEFI，若是BIOS可自己进入修改-->下一步

![photo7](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19225911_LI.md.jpg)

8.处理器数量按实际需求设置-->下一步

![photo8](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19225927_LI.md.jpg)

9.内存同理可得，自己设置-->下一步

![photo9](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19225942_LI.md.jpg)

10.注意：选择桥接网络-->下一步

![photo10](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19225958_LI.md.jpg)

11.默认-->下一步

![photo11](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19230010_LI.md.jpg)

12.默认-->下一步

![photo12](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19230028_LI.md.jpg)

13.注意：选择物理磁盘-->下一步

![photo13](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19230103_LI.md.jpg)

14.注意：选择目标磁盘-->使用整个磁盘-->下一步

![photo14](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19230158_LI.md.jpg)

15.文件位置默认即可-->下一步

![photo15](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19230222_LI.md.jpg)

16.最后完成安装

![photo15](http://pgl888999.asuscomm.com:666/images/2020/04/19/Inked2020-04-19230241_LI.md.jpg)

![photo16](http://pgl888999.asuscomm.com:666/images/2020/04/19/2020-04-19230309.md.png)

17.启动虚拟机，并更新至最新的Windows！！一定要更新至最新！！不能有任何未更新项

18.下载并复制"install.ps1"到新配置的计算机上。

19.以管理员身份打开PowerShell。

20.通过运行取消阻止安装文件 。

`Unblock-File .\install.ps1`

21.通过运行启用脚本执行:

`Set-ExecutionPolicy Unrestricted -f`

22.最后，执行安装程序脚本，如下所示：

`.\install.ps1`

您还可以将密码作为参数传递： 

`.\install.ps1 -password <password>`

该脚本将设置Boxstarter环境，并继续下载并安装Commando VM环境。系统将提示您输入管理员密码，以便在安装过程中自动重启主机。如果未设置密码，则在出现提示时按Enter。

* 自定义安装:

1.从[此链接](https://github.com/fireeye/commando-vm)下载zip到您的Downloads文件夹中。

2.通过删除工具或在“程序包”部分中添加工具来解压缩zip并编辑文件。可从我们的包装清单或巧克力仓库中获得工具。

`${Env:UserProfile}\Downloads\commando-vm-master\commando-vm-master\profile.json`

3.打开一个管理性PowerShell窗口并启用脚本执行。 

`Set-ExecutionPolicy Unrestricted -f`

4.转到解压缩的项目目录。 

`cd ${Env:UserProfile}\Downloads\commando-vm-master\commando-vm-master\`

5.使用-profile_file参数执行安装。 

`.\install.ps1 -profile_file .\profile.json`

更多参阅FireEye的[博客](https://www.fireeye.com/blog/threat-research/2019/08/commando-vm-customization-containers-kali.html)。

套件出自FireEye,[GitHub地址](https://github.com/fireeye/commando-vm)。
