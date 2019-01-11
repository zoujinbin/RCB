# RCB APP更新上传机制

| Author | Email |
| :----: | :----: |
| zoujinbin | zoujb1990@gmail.com |


## 修改APP版本号
### Android平台
* 修改**android/app/build.gradle**文件*defaultConfig*下的*versionName*属性，比如versionName "1.1.4"

### IOS平台
* 修改**ios/Runner/Info.plist**文件下的*CFBundleShortVersionString*属性，比如修改成"1.1.4" 


## APP 打包命令
``` flutter build apk --target-platform android-arm64 ```


## *GitHub*上新增相应版本号
* **url地址**：https://github.com/zoujinbin/RCB
* 新增相应的release版本号,确保新增的版本号大于手机端已安装app的版本号
1. 点击下图红色方框的releases
![image](https://github.com/zoujinbin/RCB/raw/master/Github1.jpg)

2.点击下图红色方框的*Draft a new release*，新建1.1.4版本号 ，可参考其他release
![image](https://github.com/zoujinbin/RCB/raw/master/Github2.jpg)
![image](https://github.com/zoujinbin/RCB/raw/master/Github3.jpg)


## 上传蒲公英
* **url地址**：https://www.pgyer.com/
* 点击首页的**应用上传**按钮上传app即可，会自动识别app名称和版本号；
