# Genshin-PC-Touchscreen
# 原神PC版使用触屏
![PixPin_2023-12-13_15-34-45](https://github.com/Omoinemie/Genshin-PC-Touch/assets/31991443/2120131d-27f8-423c-8c54-05bb35026f82)


## 方法一：
在游戏启动程序Yuanshen.exe或者GenshinImpact.exe目录下创建一个bat脚本。
### 国服：
```
YuanShen.exe use_mobile_platform -is_cloud 1 -platform_type CLOUD_THIRD_PARTY_MOBILE
```
### 国际服：
```
GenshinImpact.exe use_mobile_platform -is_cloud 1 -platform_type CLOUD_THIRD_PARTY_MOBILE
```
## 方法二：
将Yuanshen.exe或者GenshinImpact.exe创建快捷方式到其他目录，单击快捷方式属性，在目标这一栏里面修改成如下，注意将路径修改成自己的游戏路径：
### 国服：
```
"F:\Genshin Impact\Genshin Impact Game\YuanShen.exe" use_mobile_platform -is_cloud 1 -platform_type CLOUD_THIRD_PARTY_MOBILE
```
### 国际服：
```
"F:\Genshin Impact\Genshin Impact Game\GenshinImpact.exe" use_mobile_platform -is_cloud 1 -platform_type CLOUD_THIRD_PARTY_MOBILE
```
注意，需要先启动launcher.exe，挂在后台，不然会报错。
