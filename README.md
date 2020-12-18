# Useful ADB Commands 

## 🔰Entering the shell - 

```
adb devices
adb shell
```
## 🔰Checking Android Version -

```
getprop ro.build.version.release 
```


## 🔰List all the installed apps - 

```
pm list packages
```

## 🔰Uninstalling an app (even system apps) - 

```
pm uninstall -k --user 0 com.name.ofThePackage
```

## 🔰Gettings CPU info -

```
dumpsys cpuinfo
```
## 🔰Gettings RAM info -

```
dumpsys meminfo
```
## 🔴Rebooting -

```
adb reboot
```

### <a href="https://www.automatetheplanet.com/adb-cheat-sheet/">Find more 🌎</a>