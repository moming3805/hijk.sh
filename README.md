# hijk.sh
### v2raytech.com脚本(不全)备份整理, 附带个人自用修复root检测
&nbsp;
#### `Original`: 原版未改动
#### `Fixed`: 个人修复了在使用`zh_cn`等语言时无法正常检测root的问题
&nbsp;
```
centos_install_v2ray2.sh  #v2ray带伪装一键脚本
ubuntu_install_v2ray2.sh  #v2ray带伪装一键脚本Ubuntu版
```
```
v2ray.sh                  #V2ray多合一脚本,支持VMESS+websocket+TLS+Nginx,VLESS+TCP+XTLS,VLESS+TCP+TLS等组合
xray.sh                   #Xray一键脚本
```
```
trojan.sh                 #trojan一键脚本
trojan-go.sh              #trojan-go一键脚本
```
```
ssr.sh                    #ShadowsocksR/SSR一键脚本
ss.sh                     #Shadowsocks/SS一键脚本
```
```
mtproto.sh                #MTProto一键脚本
wordpress.sh              #WordPress一键脚本，v2ray伪装建站
wordpress_trojan.sh       #WordPress一键脚本，trojan伪装建站
```
```
#阿里云卸载云盾/安骑士
bash <(curl -sL http://update.aegis.aliyun.com/download/uninstall.sh)
bash <(curl -sL http://update.aegis.aliyun.com/download/quartz_uninstall.sh)
pkill aliyun-service
rm -rf /etc/init.d/agentwatch /usr/sbin/aliyun-service
rm -rf /usr/local/aegis*
```
```
#腾讯云监控软件卸载
/usr/local/qcloud/stargate/admin/uninstall.sh
/usr/local/qcloud/YunJing/uninst.sh
/usr/local/qcloud/monitor/barad/admin/uninstall.sh
```
