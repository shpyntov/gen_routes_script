# gen_routes_script
Generate ip route filter rules 

```curl -s https://community.antifilter.download/list/community.lst | awk {'print "ip route add "$1" dev wg0"'}```
