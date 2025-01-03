ShadowsocksR
===========

把自己需要的放到了一起，删除了自己用不到的一些东西。可能无法运行，请勿使用。

    wget -N --no-check-certificate https://raw.githubusercontent.com/ymkf/shadowsocksr/main/ssr.sh && chmod +x ssr.sh && bash ssr.sh
    
加速使用：BBR+CAKE或BBRP+FQ

    wget --no-check-certificate https://raw.githubusercontent.com/jinwyp/one_click_script/master/install_kernel.sh && chmod +x ./install_kernel.sh && ./install_kernel.sh
    
其他

    /usr/local/share/assist-daemon/assist_daemon --stop
    /usr/local/share/assist-daemon/assist_daemon --delete
    rm -rf /usr/local/share/assist-daemon
    sudo rpm -qa | grep aliyun_assist | xargs sudo rpm -e
    rm -rf /usr/local/share/aliyun-assist
    bash /usr/local/cloudmonitor/cloudmonitorCtl.sh stop
    bash /usr/local/cloudmonitor/cloudmonitorCtl.sh uninstall
    rm -rf /usr/local/cloudmonitor
    wget http://update.aegis.aliyun.com/download/uninstall.sh && chmod +x uninstall.sh && ./uninstall.sh
    wget http://update.aegis.aliyun.com/download/quartz_uninstall.sh && chmod +x quartz_uninstall.sh && ./quartz_uninstall.sh
    pkill aliyun-service
    rm -fr /etc/init.d/agentwatch /usr/sbin/aliyun-service
    rm -rf /usr/local/aegis*
    rm -rf /etc/systemd/system/aliyun.service
    rm -rf /etc/systemd/system/AssistDaemon.service
    rm -rf /etc/systemd/system/cloudmonitor.service
    iptables -I INPUT -s 140.205.201.0/28 -j DROP
    iptables -I INPUT -s 140.205.201.16/29 -j DROP
    iptables -I INPUT -s 140.205.201.32/28 -j DROP
    iptables -I INPUT -s 140.205.225.192/29 -j DROP
    iptables -I INPUT -s 140.205.225.200/30 -j DROP
    iptables -I INPUT -s 140.205.225.184/29 -j DROP
    iptables -I INPUT -s 140.205.225.183/32 -j DROP
    iptables -I INPUT -s 140.205.225.206/32 -j DROP
    iptables -I INPUT -s 140.205.225.205/32 -j DROP
    iptables -I INPUT -s 140.205.225.195/32 -j DROP
    iptables -I INPUT -s 140.205.225.204/32 -j DROP

修改自：

https://github.com/ToyoDAdoubiBackup/shadowsocksr

https://github.com/ToyoDAdoubi/doubi

加速等功能：

https://github.com/jinwyp/one_click_script
