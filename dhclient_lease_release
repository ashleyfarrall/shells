#/bin/bash

interface=$(ls /sys/class/net | head -n 1)
echo "$interface"
/usr/sbin/dhclient -1 $interface
