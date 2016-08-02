# iOSOPenDevInstall

#### MacPorts

安装MacPorts后打开终端执行：

sudo port -v selfupdate     //更新MacPorts到最新版本。

sudo port -f install dpkg   //安装DPKG文件,该文件用于打包.deb文件。

#### those

export THEOS=/opt/theos 

git clone -b stableversion https://github.com/haorenqq/theos/ $THEOS

#### ldid

sudo cp -f ./ldid $THEOS/bin/ldid

#### IOSOpenDev

安装IOSOpenDev，肯定失败，失败后执行：

sudo /opt/iOSOpenDevSetup/bin/iod-setup base

#### 配置免密ssh连接手机

iosod sshkey -h your.iphone.ip.address
