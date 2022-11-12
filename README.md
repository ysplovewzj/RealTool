# RealTool


## 软件声明
此工具语言为Python【3.8.10】，GUI是PyQt5【PyQt5==5.14.2】，打包是用pyinstaller，360可能会报毒，所有设置都保存在本地，介意勿下！

## 关于RealTool
RealTool是一款获取直播源链接的软件，支持获取【**斗鱼**】【**虎牙**】【**B站**】【**抖音**】【**YY**】【**酷我**】【**酷狗**】【**一直播**】的直播源链接，并且支持录制等功能！
有任何问题可以发Issues，也可以加入聊天群【1134070718】进行问题反馈！

## 关于开源
本软件的获取链接是基于两位大佬的开源项目
1. 获取直播源开源链接wbt5：https://github.com/wbt5/real-url
2. m3u8录制开源链接nilaoda：https://github.com/nilaoda/N_m3u8DL-RE


### 2022年10月22日
**修复虎牙斗鱼直播源无法正确获取的问题，这是上版本修改过程中出现的BUG，现已修复！**
**新增批量获取直播源，需要先手动添加直播间，然后输入框为空的情况下点击获取或者回车即可批量获取！**

### 2022年10月24日
**新增【YY直播】【酷我直播】【酷狗直播】**
**新增多线程访问，现在能更快的获取到直播源了**

### 2022年10月24日14:34
**修复同一平台批量获取只能获取到一个的问题**

### 2022年10月26日
**新采用Nuitka打包，理论上运行速度和兼容版本更强，只有64位【以前都是Pyinstaller打包】**
**修复批量获取只有第一个平台才能获取成功的问题**
**修复抖音直播源画质问题**

### 2022年10月27日
**新增获取主播昵称功能，获取列表和保存列表均已添加**

### 2022年10月29日
**修复YY直播获取失败的问题**
**调整虎牙画质获取方式，现在强制获取所有虎牙直播画质**

### 2022年10月31日
**修复YY直播因正则匹配原因导致软件崩溃的问题**
**新增斗鱼m3u8格式**
**根据坛友反馈MPV播放器播放几个小时都不会出现直播源失效的问题，所以推荐使用MPV播放器**
**[MPV播放器官网](https://mpv.io)**

**MPV懒人包网址**
**[MPV懒人包](https://github.com/hooke007/MPV_lazy/)**

**修复YY直播首页直播房间号获取的问题**


### 2022年11月3日
**新增【一直播】直播源获取**

### 2022年11月12日
**新增【播放设置】，现在可以选择PotPlayer或者MPVPlayer播放器**

### 2022年11月13日
**修复因目录有空格而导致打开目录错误的问题
修复因链接有特殊字符而无法用mpv播放的问题
【严禁mpv目录中有空格及特殊字符，否则将无法播放】**

