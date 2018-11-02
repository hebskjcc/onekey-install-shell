Frp-Client
===========
##作为frp的搬运工，我只是提供了一键安装脚本，至于使用的原理啊、功能啊、bug啊请各位移步到frp项目，我真的无能为力。


##感谢[fatedier/frp](https://github.com/fatedier/frp)提供这么优秀的软件
frp 是一个高性能的反向代理应用，可以帮助您轻松地进行内网穿透，对外网提供服务，支持 tcp, http, https 等协议类型，并且 web 服务支持根据域名进行路由转发。

脚本是业余爱好，英文属于文盲，写的不好，欢迎您批评指正。

安装平台：CentOS、Debian、Ubuntu。


Client
------

### Install

```Bash
wget --no-check-certificate https://raw.githubusercontent.com/hebskjcc/onekey-install-shell/master/frpc/install-frpc.sh -O ./install-frpc.sh
chmod 700 ./install-frpc.sh
./install-frpc.sh install
```

### UnInstall
```Bash
    ./install-frpc.sh uninstall
```
### Update
```Bash
    ./install-frpc.sh update
```
### 服务器管理
```Bash
    Usage: /etc/init.d/frpc {start|stop|restart|status|config|version}
```

