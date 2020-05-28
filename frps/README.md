Frp-Server
* 详情：fatedier (https://github.com/fatedier/frp)
* 此脚本原作者：clangcn (https://github.com/clangcn/onekey-install-shell)


安装平台：CentOS、Debian、Ubuntu。


Server
------

### Install

```Bash
wget --no-check-certificate https://raw.githubusercontent.com/WeiKKJ/onekey-install-shell/master/frps/install-frps.sh -O ./install-frps.sh
chmod 700 ./install-frps.sh
./install-frps.sh install
```

### UnInstall
```Bash
    ./install-frps.sh uninstall
```
### Update
```Bash
    ./install-frps.sh update
```
### 服务器管理
```Bash
    Usage: /etc/init.d/frps {start|stop|restart|status|config|version}
```
