# adb打開android熱點usb共享網絡

adb打開android熱點usb共享網絡

1.下載adb軟體，並開啟手機的usb調試功能

adb下載地址

| 1 | `https://developer.android.google.cn/tools/releases/platform-tools?hl=zh-tw` |
| --- | --- |

2.進入adb資料夾，使用adb命令連接手機，此時如果檢測到手機，手機會跳出提示“允許調試”，在手機上點擊“一律允許調試”，下次就自動連接不會提示了

| 12 | `cd` `C:\platform-tools.\adb.exe devices` |
| --- | --- |

3.adb控製手機打開usb熱點

| 12 | `#可能的值'mtp', 'ptp', 'rndis', 'midi', 'none'adb shell svc usb setFunctions rndis` |
| --- | --- |

adb: [https://developer.android.google.cn/tools/releases/platform-tools?hl=zh-tw](https://developer.android.google.cn/tools/releases/platform-tools? hl=zh-tw)

來源: [https://www.cnblogs.com/difs/p/18512115](https://www.cnblogs.com/difs/p/18512115)
