# adb打开android热点usb共享网络

adb打开android热点usb共享网络

1.下载adb软件，并打开手机的usb调试功能

adb下载地址

| 1 | `https://developer.android.google.cn/tools/releases/platform-tools?hl=zh-cn` |
| --- | --- |

2.进入adb文件夹，使用adb命令连接手机，此时如果检测到手机，手机会跳出提示“允许调试”，在手机上点击“一律允许调试”，下次就自动连接不会提示了

| 12 | `cd` `C:\platform-tools.\adb.exe devices` |
| --- | --- |

3.adb控制手机打开usb热点

| 12 | `#可能的值'mtp', 'ptp', 'rndis', 'midi', 'none'adb shell svc usb setFunctions rndis` |
| --- | --- |

adb: [https://developer.android.google.cn/tools/releases/platform-tools?hl=zh-tw](https://developer.android.google.cn/tools/releases/platform-tools?hl=zh-tw)

來源: [https://www.cnblogs.com/difs/p/18512115](https://www.cnblogs.com/difs/p/18512115)