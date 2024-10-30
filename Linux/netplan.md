# Static IP on Ubuntu 22.04
```
network:
  ethernets:
    ens160:
      dhcp4: no
      addresses:
        - 192.168.10.198/24
      gateway4: 192.168.10.1
      nameservers:
        addresses:
          - 203.142.82.222
          - 203.142.84.222
  version: 2
```