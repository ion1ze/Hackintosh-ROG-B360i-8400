# Hackintosh-ROG-B360i-8400

## 配置
* CPU: i5-8400
* 主板: ROG-B360i
* 内存: 光威单条16GB
* 硬盘: 海康威视C2000
* 显卡: RX560（肥猫家）
* 网卡/蓝牙: 博通BCM94360CS2
* 显示器: AOC U2790PQU 4K 27英寸

## 状态
MacOS 10.15.7 (当前使用)
WiFi、蓝牙正常、隔空投送正常

## TODO
- [ ] 开机的时候会在第二屏之前卡30S(查了一下和硬盘Trim扫描相关)

## 主板BIOS设置
* CFGLock -> Disabled
* VT-d -> Disabled
* 大于4G地址空间解码 -> Enabled
* DVMTPre-Allocated -> 128M
* Systemtime and Alarm Source -> Legacy RTC
* SATA模式选择 -> AHCI（必须设置）
* legacyUSB支持 -> Enabled
* XHCIHand-off -> Enabled
* 快速启动 -> Disabled
* 开启CSM -> Disabled
* 安全启动状态 -> 关闭
* 操作系统类型 -> 其他操作系统

## 仓库
码云：`https://gitee.com/focuxin/Hackintosh-ROG-B360i-8400`

## Latest

因为本人退坑黑苹果，相关硬件已经出了，本EFI无法继续维护。

## 2021-4-18更新
* 重新定制USB

## 2021-2-24更新
* 添加GUI支持

## 2021-2-9更新
* 定制USB
* 删除无用补丁
* 优化启动速度

## 2021-2-6更新
* 更新OpenCore 0.6.6
* 其他补丁啥的都更新了
* 取消定制USB,具体定制USB可看这篇文章[黑苹果Catalina 15.x USB定制（Asrock Z370）](https://blog.csdn.net/LeoForBest/article/details/103247824)

## 2020-7-24更新
* 更新OpenCore 0.6.0


