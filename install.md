# 安装手册

## 1.下载并安装最新版Anaconda3.7 64位

下载地址如下：[Anaconda Distribution](https://www.anaconda.com/products/individual)
 
其他版本的下载地址:https://repo.anaconda.com/archive/

由于脚本中都是基于python3.7,但最新的anaconda是3.8的python，需要切换一下[python-3-7-package-build](https://www.anaconda.com/blog/python-3-7-package-build-out-miniconda-release):   
`conda install python=3.7 anaconda=custom`

## 2.下载 visualstudio

下载地址如下: https://visualstudio.microsoft.com/zh-hans/thank-you-downloading-visual-studio/?sku=Professional&rel=16
下载并安装C++桌面开发环境。


## 3.下载并解压vnpy
进入vnpy的github主页vnpy。 在左方的Branch选项，master对应是最新的稳定版本，dev对应的是最新测试版本； 然后在主页右方绿色的clone or download选项，选择Download ZIP来下载压缩版本到本地电脑。


## 4.安装vnpy
双击install.bat一键安装vnpy：

先安装ta_lib库和ib api

然后安装requirements.txt文件内相关依赖库

最后复制vnpy到Anaconda内


## 5.启动VN Trader
在文件夹tests\trader中找到run.py文件。按住“Shift” + 鼠标右键进入cmd窗口，输入下面命令即可启动VN Trader。

python run.py 
   