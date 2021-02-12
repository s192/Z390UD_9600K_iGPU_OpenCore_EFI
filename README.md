# Z390UD_9600K_iGPU_OpenCore_EFI

## 备注

* 基于 OpenCore 0.6.6，移除 PlatformInfo 中的 SystemSerialNumber 等信息，请务必自己生成！
* 无线网卡不带蓝牙，暂无相关需求未增加硬件。心水 Asus BT-400、VCK BTD08，奈何前者太贵，后者不了解。有合适渠道或替代欢迎提供建议。
* 主板无 DP 口，显示器连接方式为 HDMI 直连。

## 配置

|      |                                    |
| :------: | :----------------------------------------: |
|  处理器  |        Intel i5-9600K                        |
|   主板   |        Gigabyte Z390 Ultra Durable™           |
|   显卡   |        Intel® UHD Graphics 630               |
|   内存   |        HyperX® FURY DDR4 16GB 2666MHz |
|   存储   |        SAMSUNG 860 EVO SATA M.2 SSD 500GB                     |
|  显示器  |        DELL U2417H         |
|   声卡   |        Realtek® ALC887                       |
|   无线网卡   |        TP-LINK TL-WDN7280                          |

## 待解决

* iStat Menus 无法监测温度及 GPU，但 Intel® Power Gadget 可以。
* 声卡信息暂时参数注入，未改写到 DeviceProperties 中。
