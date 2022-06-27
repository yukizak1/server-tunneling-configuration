## Run As Root

## Stunnel Websocket

`mkdir -p /etc/stunnel/`

`wget 'https://raw.githubusercontent.com/yukizak1/server-tunneling-configuration/main/stunnel.conf' -O /etc/stunnel/stunnel.conf`

`wget 'https://raw.githubusercontent.com/yukizak1/server-tunneling-configuration/main/ws-tls' -O /usr/local/bin/ws-tls`

`wget 'https://raw.githubusercontent.com/yukizak1/server-tunneling-configuration/main/ws-tls.service' -O /etc/systemd/system/ws-tls.service`

`chmod +x /etc/stunnel/stunnel.conf`

`chmod +x '/usr/local/bin/ws-tls'`

`chmod +x '/etc/systemd/system/ws-tls.service'`


## Xray Config

xray shadowsocks websocket tls

`wget 'https://raw.githubusercontent.com/yukizak1/server-tunneling-configuration/main/xray/00_log.json' -O /usr/local/etc/xray/00_log.json`

`wget 'https://raw.githubusercontent.com/yukizak1/server-tunneling-configuration/main/xray/01_dns.json' -O /usr/local/etc/xray/01_dns.json`

`wget 'https://raw.githubusercontent.com/yukizak1/server-tunneling-configuration/main/xray/02_inbounds.json' -O /usr/local/etc/xray/02_inbounds.json`

`wget 'https://raw.githubusercontent.com/yukizak1/server-tunneling-configuration/main/xray/03_outbounds.json' -O /usr/local/etc/xray/03_outbounds.json`



