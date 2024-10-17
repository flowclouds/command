# 1.adb 查看当前Activity

```shell
adb shell "dumpsys activity top | grep ACTIVITY | tail -n 1"
```

# 2.magisk修改ro.debuggable 

```shell
adb shell #adb进入命令行模式

su #切换至超级用户

magisk resetprop ro.debuggable 1

stop;start; #一定要通过该方式重启
```
