安装说明
=============

[![English badge](https://img.shields.io/badge/%E8%8B%B1%E6%96%87-English-blue)](./Installation.md)
[![简体中文 badge](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Simplified%20Chinese-green)](./Installation-zh_cn.md)

硬件要求
----

*   Arduino UNO控制板
*   Arduino 扩展板
*   供电板
*   4个麦卡纳姆轮
*   2个电机驱动板
*   4个JGB37-520直流电机
*   3D打印好的主体模型
*   蓝牙模块（可选）
*   12V电池或其他合适的电源
*   杜邦线、螺丝等小配件

软件要求
----

*   Arduino IDE

安装步骤
----

1. **下载代码**

   在[main.ino](https://github.com/CassiusXiang/OmniRob/tree/main/Software/main)下载麦卡纳姆轮智能小车代码。

2. **连接硬件**

   将Arduino UNO控制板插入电脑，使用杜邦线连接直流电机以及其他扩展模块。

3. **打开Arduino IDE**

   打开Arduino IDE软件，将代码文件打开。点击"Tools"->"Board"，选择"Arduino Uno"作为板子。

4. **上传代码**

   点击"Sketch"->"Upload"上传代码。

5. **控制小车**

   打开蓝牙串口调试助手，在设备列表中找到蓝牙模块并连接。在调试助手中输入命令，就可以控制小车前进、后退、左转、右转等动作。

实物样例
----

组装完成的实物图：

![](3.Image/2.jpg)

接线示意图：

![](3.Image/3.jpg)

注意事项
----

*   在安装过程中，请仔细阅读代码中的注释，并正确连接硬件。
*   使用蓝牙串口调试助手时，请确保设备列表中已找到蓝牙模块并连接成功。
*   在控制小车时，请注意安全。不要将小车放在不平衡或易倾斜的表面上，以免发生意外。
*   请参考实物图进行安装，注意麦卡纳姆轮的方向
*   接线请参考接线示意图

