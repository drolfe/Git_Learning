this is a test readme file

```bash
# this NIC must be on management network
auto eth1
iface eth1 inet static
    address 10.200.10.10
    netmask 255.255.255.0
    gateway 10.200.10.1
    dns-nameservers 8.8.8.8 8.8.4.4
```

