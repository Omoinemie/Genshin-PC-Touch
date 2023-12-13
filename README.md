# Genshin-PC-Touch
# 原神PC版使用触屏
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
