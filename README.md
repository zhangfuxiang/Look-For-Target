# 简介 #
**该项目是基于现实增强库Artoolkit，在Unity上进行开发的。实现目标指引功能并适用在Hololens上的AR应用。**
# 运行步骤 #
1. 解压HoloLensARToolKit(Unity)压缩包。
2. 用Unity3D打开项目中的HoloLensARSample文件夹。
3. 运行的scene是Sample文件夹下的HoloLensARToolKitSingle。
4. 将项目build成可在VS上打开的UMP项目(具体操作参考Microsoft HoloLens官网)，只需要对HoloLensARToolKitSingle进行build。
5. 然后用VS运行build出来的项目，然后电脑接HoloLens设备将程序安装进去，这样就可以运行该应用了（VS中要包含window10 SDk）。

# 注意 #
在选择目标页面有设置一个远近的选项，“远”代表识别距离在0.5m-1m范围内，识别的marker与呈现的3d模型校准。“近”代表识别距离在0.2m左右范围，识别的marker与呈现的3d模型校准。


# 结语 #

本应用借鉴了此开源项目:[https://github.com/qian256/HoloLensARToolKit](https://github.com/qian256/HoloLensARToolKit)
