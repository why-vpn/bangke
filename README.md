```
apt update && apt upgrade -y && update-grub && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/why-vpn/bangke/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
```
