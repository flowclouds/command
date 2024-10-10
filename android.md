# 1.adb 查看当前Activity

```shell
adb shell "dumpsys activity top | grep ACTIVITY | tail -n 1"
```
