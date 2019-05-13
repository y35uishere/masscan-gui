
------------

## 简介

[masscan](https://github.com/robertdavidgraham/masscan "masscan")号称是世界上最快的扫描软件，可以在3分钟内扫描整个互联网端口，但是这个是由条件的4核电脑，双端口10G网卡。

masscan相比nmap之所以快很多，masscan采用了异步传输方式，无状态的扫描方式。nmap需要记录tcp/ip的状态，os能够处理的TCP/IP连接最多为1500左右。

由于masscan没有图形界面，所以这个工具诞生了！



------------


### 下载地址 download link 
主程序[点击下载](https://cdn.lr3800.52qdw.cn/0.6.7z "https://cdn.lr3800.52qdw.cn/0.6.7z") 

[完整]主程序+运行库 [点击下载](https://cdn.lr3800.52qdw.cn/Orange-port-scanner.7z "点击下载")

 支持语言： 英语、 俄罗斯语、简体中文、繁体中文、土耳其语
 
 支持系统：WIN7/WIN8/WIN10   不支持XP/2003

**注意：**

依赖 [WinPcap](https://www.winpcap.org/install/bin/WinPcap_4_1_3.exe "WinPcap")，安装后才可使用扫描，[点击下载](https://www.winpcap.org/install/bin/WinPcap_4_1_3.exe "点击下载") 

如果出现其他错误，不能正常扫描；检测是否缺少微软运行库！[点击下载](https://lr3800.com/download/MSVBCRT.AIO.2019.04.24.x64.exe "点击下载")


## 使用方法：
输入IP地址格式：
支持批量导入
192.168.0.1
192.168.0.1/24
192.168.0.1/16
192.168.0.1-192.168.0.254

发包速度：<30k

如果不是大范围扫描，建议默认在10000之间。 由于windows系统差异，理论最大速度30万，根据自己电脑配置和宽带合理使用；否则很容易占用大量宽带造成局域网瘫痪

支持PING扫描和端口扫描
PING 探测存活主机
[![](https://i.loli.net/2019/05/05/5ccea9b195c0c.png)](https://i.loli.net/2019/05/05/5ccea9b195c0c.png)
端口扫描 探测开放服务
[![](https://i.loli.net/2019/05/05/5ccea9c2ee183.png)](https://i.loli.net/2019/05/05/5ccea9c2ee183.png)


------------



仅限用于学习和研究目的；不得将上述内容用于商业或者非法用途，否则承担全部法律及连带责任，安全猎人不承担任何法律及连带责任。您必须在下载后的24个小时之内，从您的电脑中彻底删除上述内容。
参见 [免责声明](https://lr3800.com/disclaimer/ "免责声明")
