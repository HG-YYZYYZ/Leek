# 我的云钢厂——老韭民的期货量化交易分析软件

正式版v3.0  使用说明

------------

#### 简介

本软件是基于Python3的轻量级数据采集及计算软件，目的在于辅助期货量化交易，帮助期货交易散户更方便的获取相关数据。

#### 更新内容

v3.0 将外置图表框整合入主窗口中

v2.4 对于期货日期代码输入方式进行了更新。

v2.1 对图形界面的一些小优化,调大了显示字体。增加了存储功能。

v2.0 增加了GUI图形界面

v1.1 增加了绘制图样的功能，可以绘制一段时间内的螺纹钢市场价和理论成本价折线图

#### 主要功能

该测试版软件实现的功能为实时（每5秒）采集期货中螺纹钢、铁矿石、焦炭三件大宗商品的价格，并根据公式组计算而得。
公式：

	生铁成本 ＝（1.6 × 铁矿石 + 0.45 × 焦炭）/ 0.9
	粗钢成本 ＝（0.96 × 生铁 + 0.15 × 废钢）/ 0.82
	螺纹钢成本 = 粗钢成本 + 制造成本（螺纹钢轧制成本）
	（注意：1、0.9是指原材料大致占的费用比例，0.82类似；2、螺纹钢轧制成本计250元）

#### 运行环境安装及配置

首先安装Python

建议直接安装最新版的Python3

![](https://qwdi8008ibwp.xyz/IHS/v0.1/1.png)

先安装Python

## 安装时请记得将其添加到Path

![](https://qwdi8008ibwp.xyz/IHS/v0.1/2.png)

这个时候，系统可能会弹出“是否允许此应用对你的设备进行更改”

点击“是”即可

![](https://qwdi8008ibwp.xyz/IHS/v0.1/3.png)

然后等待安装完成

![](https://qwdi8008ibwp.xyz/IHS/v0.1/4.png)

当出现如下画面，点击close完成安装

![](https://qwdi8008ibwp.xyz/IHS/v0.1/5.png)

接着点击文件夹目录中的setup.bat文件，对必要的库进行安装

![](https://qwdi8008ibwp.xyz/IHS/v0.1/6.png)

双击打开后不用进行任何操作

当提示“请按任意键继续”时表示已经安装完成，按任意键关闭命令框

![](https://qwdi8008ibwp.xyz/IHS/v0.1/7.png)

由于版本更新，此处不再需要调整命令框的字体大小

自此，整个安装过程全部完成

接下来就可以正常使用这个软件了

退出程序只需要关闭黑色命令框即可退出