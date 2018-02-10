# Multi-Machine-Fusion
多机同步播放拼接融合系统(Multi-Machine-Fusion)

  此系统完成将多投影仪画面进行空间拼接和混合。此系统是个人从事展览展示行业多年的研发成果和精力完成的一套一体化软件。
此系统的前身是在2012年的一个测试版本中改进而来，经过2年的改进和完善最终达到本系统的1.3.2正式版本。
  本人对于技术的爱好所以决定在5、6年后将此软件进行开源化。系统中也存在一些暂未完成功能。但是此版本已经满足市面上的大部分应用，
并且在多PC模式下具备很好的调试技术。此软件从问世到现在应用过很多商业领域以及很多扩展领域，并且应用十分稳定。
  由于本开源系统供参考和研究，不做商业应用则已经将许可证使用、保存数据和加载数据部分删除。若需要用商业应用可联系本人。

系统的组成和实现细节:
   1.使用跨平台Qt完成Ui界面的定制;
   2.使用OpenGL实现几何调整、图像的输出、图像混合、图像合成功能;
   3.可将平台依赖部分做修改可支持Windows、Linux、Mac、Android、Wayland、Mir
   4.当前实现的平台部分支持Windows

下面是系统的功能基本描述：
   1.支持水平、垂直多台计算机融合；
   2.支持单台计算机水平、垂直融合；(可多台计算机组合)
   3.支持桌面镜像；
   4.支持任意形状校正；(a.弧幕。b.数字沙盘。c.建筑投影。d. 天幕。e.穹幕。f.球型(内外)。g.CAVE空间。)
   5.支持融合带任意位置和任意宽度；
   6.支持每通道单边融合带调整；
   7.支持每通道颜色校正；(亮度、饱和度、色度、色调、基色调整、alpha调整)
   8.支持输入任何图像任意裁剪；
   9.支持鼠标、键盘调整几何；
   10.支持曲面调整、点调整；
   11.支持任意可用视频格式；
   12.支持任意可用图片格式；
   13.支持网络控制；
   14.支持多机同步；
   15.支持数字沙盘时间节点控制；
   16.支持PJlink控制；
   17.支持计算机控制；(a.关机。b.重启。c.系统音量[Win10暂有bug]。d.系统键盘鼠标映射)
   18.支持自定义背景图；
   19.支持随系统自动启动；
   20.支持自动加载数据；
   21.支持时间限制；
   22.支持鼠标隐藏；
   23.支持窗口及多图层合成;
   24.多视频格式支持硬件解码，少数格式采用软解码;
