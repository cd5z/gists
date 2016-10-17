# Xocde8 隐藏无用log

```
Edit Scheme-> Run -> Arguments, Environment Variables
OS_ACTIVITY_MODE ＝ Disable 
```

# Xcode Http

```
<key>NSAppTransportSecurity</key>
<dict>
    <key>NSAllowsArbitraryLoads</key>
    <true/>
</dict>
```

# 查看项目代码行数

```
find . -name "*.m" -or -name "*.h" -or -name "*.xib" -or -name "*.c" -or -name "*.storyboard"|xargs grep -v "^$"|wc -l
```

# Xcode 多个模拟器解决方法

```
sudo killall -9 com.apple.CoreSimulator.CoreSimulatorService
rm -rf ~/Library/Developer/CoreSimulator/Devices
```
