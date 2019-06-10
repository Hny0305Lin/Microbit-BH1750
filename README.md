# BH1750
makecode 的 BH1750 数字环境光强传感器 microbit 软件包

作者: 朱林  
日期: 2018/4

![image](https://github.com/zhuning239/BH1750/blob/master/icon.png)  
  
![image](https://github.com/zhuning239/BH1750/blob/master/GY-30.jpg)

## 使用方法

打开 makecode 编辑器，在项目中选择添加软件包，然后在地址栏输入下面网址  

https://github.com/zhuning239/BH1750

搜索后就可以添加并使用本软件包了。

## I2C 地址  
- 35/92  
与ADDR信号有关 

## API

- **SetAddress**(addr: BH1750_ADDRESS)  
to 是 BH1750 的I2C地址，它是 35 或 92  

- **on**()  
打开 BH1750，开始进行数据转换。

- **off**()
关闭 BH1750，进入省电模式。

- **getIntensity**()  
获取环境光强度的数据

## 演示

![image](https://github.com/zhuning239/BH1750/blob/master/demo.jpg)

## 授权方式

MIT

湖南创乐博智能科技有限公司

## 支持硬件

* for PXT/microbit
