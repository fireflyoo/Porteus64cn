# Porteus64cn 
- 2021-01-08 增加 小小输入法的QT模块。请使用最新的004-yong.xzm.
- 2020-12-27 增加 小小输入法+文泉驿微米黑 合体安装包
- 2020-12-26 增加 小小输入法 安装包
安装包使用方法：  
把安装包扔到/mnt/live/porteus/modules/目录下重启就行了

常用命令：
```bash
active yong*.xzm #临时安装（重启失效）
deactive yong*.xzm #临时卸载（重启失效）
lsxzm yong*.xzm #查看安装包目录
mkdir yongDIR && xzm2dir yong*.xzm yongDIR #解压安装包到yongDIR目录下
dir2xzm yongDIR #重新打包
mloop yong*.xzm #挂载安装包到/mnt/loop(只读）
```

官方安装包
http://dl.porteus.org/x86_64/testing/packages/Language-Selection-Tool/
里面有
1. odosung-文鼎PL新中楷字体
2. unifont-GNU家的字体，包含中文字体
3. wqy-zenhei-文泉驿正黑
