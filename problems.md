* [主页](README.md)
* [下载](download.md)
* [特性](feaures.md)
* [常见问题](problems.md)
* [更新日志](logs.md)

如果下面这些没有解决你的问题，请到[植物大战僵尸贴吧](https://tieba.baidu.com/f?kw=植物大战僵尸)寻找答案或者提问。

* [Windows 10 弹出 29 个 Fatal Error 弹窗](#问题windows-10-游戏安装好后弹出-29-个-fatal-error-弹窗怎么办)
* [无法存档](#问题无法存档怎么办)

## **问题：Windows 10 游戏安装好后弹出 29 个 Fatal Error 弹窗怎么办？**

![17txoQ.png](https://s2.ax1x.com/2020/02/13/1O5eKA.png)

**答案：**
最简单的解决方式是关闭全屏。如果你是从[下载页面](download.html)下载的整合包安装程序，那么安装时勾选 `Win 10 Fatal Error 修复` 即可解决：

![17tOL8.png](https://s2.ax1x.com/2020/02/13/1O5BPU.png)

如果是其他方式获取的游戏，那么请点击下载 [pvz_win10_fix.reg](/pvz_win10_fix.reg)，下载完成后双击运行即可。

如果你还需要全屏的话，那么按照以下图片操作：

![1LsplT.jpg](https://s2.ax1x.com/2020/02/13/1LsplT.jpg)

![1LsCXF.jpg](https://s2.ax1x.com/2020/02/13/1LsCXF.jpg)

![1Lrxf0.jpg](https://s2.ax1x.com/2020/02/13/1Lrxf0.jpg)

## **问题：无法存档怎么办？**

**答案：**

首先，确保你已经把游戏完全从压缩包里解压了出来，而不是在压缩包内双击打开的，没有解压的时候出现 bug 是正常现象。

对于 Windows Vista 及以上：

* 如果确定游戏已解压，将 `C:\ProgramData\PopCap Games\PlantsVsZombies\userdata` 这个文件夹（`ProgramData` 是隐藏文件夹）取消只读

* 如果依然无效或者找不到 `userdata` 文件夹，请将植物大战僵尸的游戏文件的兼容性设置改为 `Windows XP (Service Pack 3)`

* 如果依然无效，请将游戏目录下的 `userdata` 文件夹取消只读

* 如果依然无效，请右键点击游戏，选择 `以管理员身份运行`

对于 Windows XP 及以下：

* 如果确定游戏已解压，请将游戏目录下的 `userdata` 文件夹取消只读