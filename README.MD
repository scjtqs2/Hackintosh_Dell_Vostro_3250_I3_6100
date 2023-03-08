# Hackintosh_Dell_Vostro_3250_I3_6100
> 公司配的开发机，i3-6100双核，ddr3内存,sata硬盘。
### 我的电脑配置：

| 硬件名称 | 型号              |
|------|-----------------|
| CPU  | i3-6100  （机器自带） |
| 显卡   | HD530           |
| 主板   | h110            |
| 内存   | ddr3 1600 16gb  |
| 硬盘   | sata硬盘          |
| 声卡   | acl662          |



### opencore版本：
0.8.9

### macos版本：
macOS Monterey
12.6.3

### 说明
请自行修改/添加 三码

使用 `Hackintool` -> `电源` -> `螺丝刀图标` 来修复电源相关的配置

## 核显的vga口无解。请使用hdmi口连接显示器。

### Win+Mac双系统解决Win系统时间时差问题

在Windows终端下使用管理员权限运行 
```
Reg add HKLM\SYSTEM\CurrentControlSet\Control\TimeZoneInformation /v RealTimeIsUniversal /t REG_DWORD /d 1
```

### 设置默认启动项

    多系统在启动选择界面，先使用键盘移动到要启动的项，然后按Ctrl+Enter(回车键)进入系统，下次重启后默认就选中该项了


