# gen_routes_script
Generate ip route filter rules 

```curl -s https://community.antifilter.download/list/community.lst | awk {'print "ip route add "$1" dev wg0"'}```

```echo "ip route add 23.1.106.237 dev wg0" >> /etc/storage/started_script.sh```
