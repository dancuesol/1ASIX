# 1ASIX

## Hola




```bash
named-checkzone bigbrainXY.com /etc/bind/db.bigbrainXY.com
named-checkzone 11.0.10.in-addr.arpa /etc/bind/db.11.0.10
named-checkzone 12.0.10.in-addr.arpa /etc/bind/db.12.0.10
named-checkzone 13.0.10.in-addr.arpa /etc/bind/db.13.0.10

```

```bash
# Reenvío entre enp0s9 y enp0s3
/sbin/iptables -A FORWARD -i enp0s9 -o enp0s3 -j ACCEPT
/sbin/iptables -A FORWARD -i enp0s3 -o enp0s9 -m state --state ESTABLISHED,RELATED -j ACCEPT
```

```bash
# Reenvío entre enp0s10 y enp0s3
/sbin/iptables -A FORWARD -i enp0s10 -o enp0s3 -j ACCEPT
/sbin/iptables -A FORWARD -i enp0s3 -o enp0s10 -m state --state ESTABLISHED,RELATED -j ACCEPT
```
