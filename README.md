# 1ASIX

## Hola




```bash
named-checkconf
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
