# 说明

##### 1.触摸板采用*<u>深圳翰天鑫</u>* 的`HTX5330A模块`（如下图），该模块输出PS/2信号

​                               <img src="D:\_PersonalProjects\MyTouchPad\0_Tests\1.PS2toUSB\Pics\HTX5330A.jpg" alt="HTX5330A" style="zoom:25%;" />

##### 2.使用`PS2-A3模块`（如下图），将该模块触点及USB端口与该芯片进行飞线焊接可直连电脑，经测试效果良好

#####                                                       <img src="D:\_PersonalProjects\MyTouchPad\0_Tests\1.PS2toUSB\Pics\PS2-A3.jpg" alt="PS2-A3" style="zoom: 50%;" />

##### 3.`HTX5330A模块`配备有FPC插座一个，经万用表测量得其线序如下图所示。为方便测试，拟设计一个FPC转接板将触摸板的PS/2信号经USB输出至电脑。



<img src="D:\_PersonalProjects\MyTouchPad\0_Tests\1.PS2toUSB\Pics\FPC线序.jpg" alt="FPC线序" style="zoom:25%;" />

##### 4.参考下文进行设计：[老键盘接口改USB-CSDN博客](https://blog.csdn.net/u012388993/article/details/116649875)。本文采用`WIT122芯片`进行PS/2信号的转换，其数据手册如下：[WIT122UHM数据手册 - 百度文库](https://wenku.baidu.com/view/08846039f28583d049649b6648d7c1c708a10b8a.html?_wkts_=1715262128212)。

