# adb-command
useage command may help you 
#####Android开发常用逆向常用命令
1.截屏操作
 adb shell screencap -p /sdcard/tem.png 
2.录屏操作
adb shell screenrecord /sdcard/tem.mp4

3.清空应用数据
adb shell pm clear com.xx.xx
4.启动应用
am start -n com.android.browser/com.android.browser.BroserActivity
5.启动一个服务
am startservice  -n com.android.traffic/com.android.traffic.maniservice
6.查看设备的IP地址
adb shell netcfg
7.查看设备的端口号信息
adb shell netstat



