# Lenovo Y9000X 2020 9750H 4K-Hackintosh

#### 介绍
安装 ALCPlugFix-Swift 来修复扬声器切换异常问题, 终端使用以下命安装或卸载 ALCPlugFix
  
```
bash -c "$(curl -fsSL https://gitee.com/YasuStudio/fix-speaker-y9000x/raw/master/FixSpeaker-Y9000X.sh)"
```
更新OC版本为0.8.6开发版，支持Mojave & Catalina & Big Sur & Monterey & Ventura
升级big sur，支持内屏4k@60，感谢[WangRicky](http://github.com/WangRicky/Y9000X-HACKINTOSH)。
机型为16,4（请注意，这是更符合i7版本的机型，其他CPU型号使用前请自行判断风险），以获得更合适的机型模拟电源策略（长期测试发现风扇会安静一些），更改机型的同时请注意USB定制，本次更新同时更新了USBPort.kext。新增启动参数igfxagdc=0，解决TYPE-C直连DP显示器，TYPE-C转HDMI显示器输出问题。

 #### **配置** 
- 主板 HM370
- CPU i7-9750H
- 分辨率：4K
- 硬盘：西数SN750+SN550
- 网卡:博通94360Z3

#### 安装教程

1.  F2进入BIOS关闭SecureBoot，切换硬盘模式为AHCI
2.  解锁CFG Lock（可选，谨慎操作！参考CFG Lock[解锁](https://bbs.pcbeta.com/viewthread-1845189-1-1.html)）

#### 工作


- 4k显示，背光调节正常
- 耳机，麦克风，摄像头
- Wi-Fi 蓝牙 handoff airdrop
- 触控板全手势支持
- 电源管理，USB接口正常
- 读卡器
- type-c接口可以正常接U盘，接type-c扩展坞以太网卡、HDMI，DP工作正常
- 外接显示器音频输出正常
- FN热键


#### 不工作

- 指纹

