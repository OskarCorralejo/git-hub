#!/bin/bash
echo "Current User @ Hostname"
hostname
echo "CPU name and Speed"
lscpu | grep "MHz"
echo "Free and Total Memory/Swap Space"
free -h
echo "Free and Total ext4/XFS Space"
df -Th | grep "^/dev/sda1"
echo "currrent IP address and Subnet"
route -n
