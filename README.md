# pcsx2_bios-for-retroarch
如何自制一个PCSX2文件夹以使得RetroArch模拟器可以运行PS2游戏
如何自制一个PCSX2文件夹以使得RetroArch模拟器可以运行PS2游戏  
# 前言
今天想放松一下，就在我的XSS上下了RetroArch全能模拟器，又恰巧看到了PS2上有我非常想玩的《奥丁领域》，但是多次运行后发现都是闪退，于是去找教程，根据B站UP主[PlayNintendo](https://space.bilibili.com/12347423)的教程[用XBOX玩PS2游戏！教程来了](https://www.bilibili.com/video/BV18A411x72v)配置我的RetroArch时我少了一步拷贝PCSX2的BIOS的内容，而UP主所提供的BIOS下载链接又失效了，同时在网络上寻找BIOS，虽然没有找到可下载直接使用的版本，但是找到了如何制作这个文件夹，现将该步骤记录以保证日后自己再需要的时候可以随时查用。  
本文的步骤根据YouTube的[Mr. Sujano](https://www.youtube.com/channel/UCu-NRUdNtfcjdGA5Abt3JUw)博主的[PlayStation 2 (PS2) Emulator on RetroArch: PCSX2 Core (Install guide: setup / config / tutorial)](https://www.youtube.com/watch?v=Ub8ID0VXQug)步骤完成。  
感谢两位UP主(博主)的帮助，若有能力请前去为两位点赞、关注(订阅)。  
# 正式步骤  
## 1.下载PS2的BIOS  
进入[Emulator Files的PS2版块](https://emulation.gametechwiki.com/index.php/Emulator_Files#PlayStation_2)，点击[<font color=red>BIOS files</font>](https://www.mediafire.com/file/edp636rbtb77hk7/PS2_BIOS.zip/file)进入下载界面。  
[![hWJVa9.png](https://z3.ax1x.com/2021/09/05/hWJVa9.png)](https://imgtu.com/i/hWJVa9)  
在弹出的窗口中选择<font color=red>DOWNLOAD</font>  
[![hWJ0sS.png](https://z3.ax1x.com/2021/09/05/hWJ0sS.png)](https://imgtu.com/i/hWJ0sS)  
下载好后备用  
## 2.下载PCSX2  
进入[PCSX2的下载界面](https://pcsx2.net/download/releases/windows.html)，选择下方的<font color=red>PCSX2 1.6.0 Windows Binary</font>进行下载。  
[![hWJjsO.png](https://z3.ax1x.com/2021/09/05/hWJjsO.png)](https://imgtu.com/i/hWJjsO)  
下载好后备用  
## 3.组合(不知道起什么名比较好)  
首先将下载好的PCSX2解压，如图  
[![hWYnoj.png](https://z3.ax1x.com/2021/09/05/hWYnoj.png)](https://imgtu.com/i/hWYnoj)  
打开PCSX2 1.6.0文件夹，在其中新建一个文件夹重命名为<font color=red>bios</font>  
[![hWYGOU.png](https://z3.ax1x.com/2021/09/05/hWYGOU.png)](https://imgtu.com/i/hWYGOU)  
将刚刚下载的BIOS文件解压到bios文件夹中  
[![hWYYmF.png](https://z3.ax1x.com/2021/09/05/hWYYmF.png)](https://imgtu.com/i/hWYYmF)  
退回到PCSX2 1.6.0文件夹，双击**pcsx2.exe**运行  
[![hWYwf1.png](https://z3.ax1x.com/2021/09/05/hWYwf1.png)](https://imgtu.com/i/hWYwf1)  
点下一步  
[![hWYsOO.png](https://z3.ax1x.com/2021/09/05/hWYsOO.png)](https://imgtu.com/i/hWYsOO)  
继续下一步  
[![hWY4pt.png](https://z3.ax1x.com/2021/09/05/hWY4pt.png)](https://imgtu.com/i/hWY4pt)  
选择内核，根据自己的需求选择，但是选择标准我不是很清楚，因此选择了china版本的。选择后点击完成。  
[![hWtec6.png](https://z3.ax1x.com/2021/09/05/hWtec6.png)](https://imgtu.com/i/hWtec6)  
出现这个界面就OK了  
[![hWtG9I.png](https://z3.ax1x.com/2021/09/05/hWtG9I.png)](https://imgtu.com/i/hWtG9I)  
叉掉之后把原来的**PCSX2 1.6.0**的文件夹重命名为**PCSX2**(不知道不重命名是否可行，顺手改一下，不碍事)  
[![hWtdHg.png](https://z3.ax1x.com/2021/09/05/hWtdHg.png)](https://imgtu.com/i/hWtdHg)  
## 4.在XBOX上操作  
将刚刚的**PCSX2**文件夹拷到XBOX上，进入RetroArch的**LocalState\system**文件夹，把**PCSX2**文件夹拷贝到里面。可以使用XBOX上的付费文件浏览器**My files Explorers**，也可以使用模拟器作者提供的FTP应用，根据自己的情况选择。
拷贝到该位置之后，整个流程就结束了。之后就可以在RetroArch上运行PS2游戏了。
