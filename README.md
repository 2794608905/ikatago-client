# ikatago-client
这是连接ikatago-server （比如百度aistudio)的客户端。

暂时没时间写文档，有问题加群: 703409387

## 准备
1. 确保百度aistudio里的ikatago-server处于运行状态。  
   （看不懂这句话啥意思的点这里: https://aistudio.baidu.com/aistudio/projectdetail/681506?shared=1)

## 下载ikagato客户端

* [Windows 64bit版本下载](https://github.com/kinfkong/ikatago-client/releases/download/v1.0.0/ikatago-1.0.0-win64.zip) 
* [Linux版本下载](https://github.com/kinfkong/ikatago-client/releases/download/v1.0.0/ikatago-1.0.0-linux.zip) 
* [Mac OSX版本下载](https://github.com/kinfkong/ikatago-client/releases/download/v1.0.0/ikatago-1.0.0-mac-osx.zip) 
* [Windows 32bit版本下载](https://github.com/kinfkong/ikatago-client/releases/download/v1.0.0/ikatago-1.0.0-win32.zip) (不要下载这个，除非你真的系统是32bit) 

## 用法 

### Lizzie用法 
```
<ikatago程序路径> --platform aistudio --username <你设置的用户名> --password <你设置的密码>
```
比如，Windows下可能是这样子:
```
C:\xxx\ikatago.exe --platform aistudio --username kinfkong --password ******
```

### Sabaki的用法
有三行，  
第一行: 引擎名字，随便起一个名字  
第二行: 程序路径，就是ikatago在你本机的路径，比如, C:\xxx\ikatago.exe  
第三行: 运行参数: --platform aistudio --username <你设置的用户名>   --password <你设置的密码>  

