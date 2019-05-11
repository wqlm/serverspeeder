# serverspeeder锐速一键破解安装版

本破解锐速是是无限带宽版

# 特别说明
另外：重要的事情说三遍！！！

锐速不支持Openvz！！！锐速不支持Openvz！！！锐速不支持Openvz！！！

### 你可能需要：
* 如果你不知道你的机子到底是不是Openvz，请食用[《教程：一键检测VPS是Openvz还是KVM还是Xen》](http://www.91yun.co/archives/836)
* 如果你的内核不对，是Centos的话请食用[《教程：CentOS更换内核，提供锐速可用的内核下载》](http://www.91yun.co/archives/795)。

# 锐速破解版安装方法：
    wget -N --no-check-certificate https://github.com/91yun/serverspeeder/raw/master/serverspeeder.sh && bash serverspeeder.sh
# 锐速破解版卸载方法：
    chattr -i /serverspeeder/etc/apx* && /serverspeeder/bin/serverSpeeder.sh uninstall -f


锐速破解版功能：
如果内核完全匹配就会自动下载安装。
如果没有完全匹配的内核，会在界面提示可选内核，可以手动选个最接近的尝试
自动下载授权文件
自动修改配置文件
已chattr +i /serverspeeder/etc/apx*禁止修改配置文件，可以不用加hosts了
目前只支持CentOS
