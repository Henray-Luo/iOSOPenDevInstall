# iOSOPenDevInstall

安装MacPorts后打开终端:> sudo port -v selfupdate 更新MacPorts到最新版本。

更新完MacPorts后安装DPKG文件，在终端输入：> sudo port -f install dpkg 该文件用于打包.deb文件。

安装those工具：1 > export THEOS=/opt/theos 

git clone -b stableversion https://github.com/haorenqq/theos/ $THEOS

sudo cp -f ./ldid $THEOS/bin/ldid 。

安装IOSOpenDev肯定失败。执行> sudo /opt/iOSOpenDevSetup/bin/iod-setup base 手动下载。

配置免密ssh连接手机 > iosod sshkey -h your.ip.add.ress 。
