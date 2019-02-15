# ssr
服务器执行

ssr：
wget https://raw.githubusercontent.com/jinrikuaile/ssr/master/ssr.sh && bash ssr.sh -ssr

ss：
wget https://raw.githubusercontent.com/jinrikuaile/ssr/master/ssr.sh && bash ssr.sh -i jinrikuaile 1024

jinrikuaile 是密码 1024 是端口

ss卸载：
wget https://raw.githubusercontent.com/jinrikuaile/ssr/master/ssr.sh && bash ssr.sh -uninstall

bbr：
wget https://raw.githubusercontent.com/jinrikuaile/ssr/master/ssr.sh && bash ssr.sh -bbr



ssr相关命令：
启动：/etc/init.d/shadowsocks start
停止：/etc/init.d/shadowsocks stop
重启：/etc/init.d/shadowsocks restart
状态：/etc/init.d/shadowsocks status
 
配置文件路径：/etc/shadowsocks.json
日志文件路径：/var/log/shadowsocks.log
代码安装目录：/usr/local/shadowsocks

卸载命令
./shadowsocksR.sh uninstall



ss相关命令：
启动：/etc/init.d/ss-fly start
停止：/etc/init.d/ss-fly stop
重启：/etc/init.d/ss-fly restart
状态：/etc/init.d/ss-fly status
查看ss链接：ss-fly/ss-fly.sh -sslink
修改配置文件：vim /etc/shadowsocks.json


判断bbr是否成功：
sysctl net.ipv4.tcp_available_congestion_control
