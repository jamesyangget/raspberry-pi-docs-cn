# 设置/快速启动

树莓派设置向导

## 你将需要什么

### 必备（一般用途）

- [SD卡](docs/installation/sd-cards.md)
    - 我们建议使用8GB 4级SD卡，理想情况下预装 [NOOBS](docs/installation/noobs.md)。
- [显示和连接电缆](docs/setup/monitor-connection.md)
    - 任何HDMI/DVI显示器和任何电视都应该作为显示器。为获得最佳效果，请使用带有HDMI输入的设备，但其他连接可用于旧设备。
- 键盘和鼠标
    - 任何标准USB键盘和鼠标都可以与你的树莓派配合使用。
    - 支持无线键盘和鼠标
    - 对于键盘布局配置的相关选项请看[树莓派设置](docs/configuration/raspi-config.md)。
- [电源支持](docs/hardware/raspberrypi/power/README.md)
    - 树莓派可以通过USB接线供电(像大多数标准手机充电器一样)。
    - 你需要一个高质量的电源，可以为3B型提供至少2A的5V电压，或者为较早的低功率型号提供500mA的5V电源。
    - 低电流（~700mA）电源可用于基本使用，但如果耗电量太大，可能会导致树莓派重启。

### 可选项

- 以太网（网络）电缆 [仅限B/B+/2/3型号]
    - 以太网电缆用于将Pi连接到本地网络和Internet。
- [USB无线网卡](docs/configuration/wireless/README.md)
    - 或者，你可以使用USB无线网卡连接到无线网络，这需要配置。
- 音频引导
    - 可以使用标准3.5mm插孔通过扬声器或耳机播放音频。
    - 如果没有HDMI线，则需要音频线来产生声音。
    - 如果你使用HDMI线连接带扬声器的显示器，则无需单独的音频线，因为音频可以直接通过显示器播放;但如果你希望通过其他扬声器播放音频，则可以连接一根 - 这需要[配置](../configuration/audio-config.md).

## 故障排除

对于设置过程中的任何问题，请在[论坛](https://www.raspberrypi.org/forums/)搜索以获取解决方案。如果找不到，请发布你的问题，并且尽可能提供详细的细节。
