### android mulator usage:

++ 开启模拟器
emulator -avd android4.4.

++ 全新安装
adb install apkPath 
adb install C:\Users\huangmiaomiao\Desktop\TM_2.1.6.apk

adb -s emulator-5554 install C:\Users\huangmiaomiao\Desktop\tianmicaifu-dev-release.apk

++ 覆盖安装
adb install -r D:\Myfiles\APK\tianmi_android\android-debug-unaligned.apk 

++ 卸载
adb uninstall com.company.project





