# 华擎ASROCK b360m itx/ac 黑苹果EFI 

_

# 配置

| name      | product               | commet                                                       |
| --------- | --------------------- | ------------------------------------------------------------ |
| CPU       | Intel i5 9400         |                                                              |
| 主板      | asrock b360m itx/ac   | LAN: Intel® I219V <br />Audio:ALC887(layout 5)<br />Display: DP(4K@60Hz) + HDMI(4K@30Hz) + DVI  <br />M.2: Type2280 + Type2230<br />USB: 前2个, 后4个 <br />PCIe3.0x16: 1 |
| 内存      | ADATA 16G(8Gx2)       | 主板 2 x DDR4 DIMM Slots ，max 32GB                          |
| SSD       | WD M.2 512 蓝盘       |                                                              |
| HDD       | 东芝 SATA 2.5英寸  1T |                                                              |
| Wi-Fi/BT  | DW1820a               |                                                              |
| 机箱/电源 | 酷鱼T4                |                                                              |



# 黑苹果工具

## 必备工具

[Hackintool](http://headsoft.com.au/download/mac/Hackintool.zip): 黑苹果工具, 查看电脑信息, 下载 升级 kext

[ProperTree](https://github.com/corpnewt/ProperTree): 用于OpenCore

[OpenCore Configurator](https://mackie100projects.altervista.org/download-opencore-configurator/): 用于OpenCore

[OpenCore](https://github.com/acidanthera/OpenCorePkg) OpenCore github

# BIOS设置

> 支持 `Clover` 和 `OpenCore`

- Boot>Fast Boot(快速启动) → disable
- Boot>CSM(兼容性支持模块) → disable
- Advanced>CPU Configuration>CFG Lock → disable
- Advanced>Chipset Configuration>VT-d → disable
- Advanced>Intel Virtualization Technology(VT) → enable
- Advanced>USB Configuration>EHCI/XHCI Hand-off → enable
- Boot>OS Type → other types



# 参考

[黑果小兵](https://blog.daliansky.net/) [[idxdy](https://github.com/idxdy)](https://github.com/idxdy/asrock_b360m_itxac)  [精讲OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html) [显卡](https://blog.daliansky.net/Tutorial-Using-Hackintool-to-open-the-correct-pose-of-the-8th-generation-core-display-HDMI-or-DVI-output.html) [声卡](https://blog.daliansky.net/Use-AppleALC-sound-card-to-drive-the-correct-posture-of-AppleHDA.html) [DW1820a](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html)

