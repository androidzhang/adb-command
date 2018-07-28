# adb-command
useage command may help you 
#####Android开发常用逆向常用命令\n\n
1.截屏操作\n
 adb shell screencap -p /sdcard/tem.png \n
2.录屏操作\n
adb shell screenrecord /sdcard/tem.mp4\n

3.清空应用数据\n
adb shell pm clear com.xx.xx\n
4.启动应用\n
am start -n com.android.browser/com.android.browser.BroserActivity\n
5.启动一个服务\n
am startservice  -n com.android.traffic/com.android.traffic.maniservice\n
6.查看设备的IP地址\n
adb shell netcfg\n
7.查看设备的端口号信息\n
adb shell netstat\n



