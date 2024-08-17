# V1.2

**实验目的：**

MCU设计前的准备工作2

**实验内容：**

统计模块功耗

**实验结果：**

根据设计构想，模块的功耗大致如下：

①ESP32本体功耗

参考[此文章](https://blog.csdn.net/Marchtwentytwo/article/details/118116022)可知ESP32功耗最高可达**168mA**

②电子墨水屏功耗

参考[微雪电子](https://www.waveshare.net/)的[产品介绍](https://www.waveshare.net/shop/1.54inch-e-Paper-B.htm)，1.45寸电子墨水屏的刷新功耗为28.4mW，待机功耗为0.017mW

由于墨水屏大多数时间为待机模式，故功耗**忽略不计**。

③OLED屏幕功耗

参考[微雪电子](https://www.waveshare.net/)的[产品介绍](https://www.waveshare.net/wiki/0.96inch_SSD1306_OLED)，0.96寸OLED屏幕的功耗最高可达**25mA**

④2812彩灯功耗

参考网络资料可知WS2812灯珠的功耗约为12至20mA/颗，计划使用5颗，则共计**100mA**



综上，电源驱动能力应当在**200mA**以上。则此前设计的电源模块可驱动各个模块正常工作，且使用1000mAh电池的理论工作时长可达5h



**实验日期：**2024.08.19
