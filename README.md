# Increase openwrt Disk Space With USB Drive

Edited a script to support version 25.12+ and Increase Your Openwrt Router Disk Space With USB Drive

How to install ? 

📍Step 1 : Plug in USB Drive to the router

📍Step 2 : ssh remote openwrt and run this command

```
rm -f exroot.sh && wget https://raw.githubusercontent.com/Sheridan8202/Increase-openwrt-disk-space/refs/heads/main/exroot.sh && chmod 777 exroot.sh && sh exroot.sh
```


- Done ! After Reboot Login to openwrt And Check Status Page Storage | Disk Space ✅

- IF You have problem please Try another USB Drive And Run Command again .
