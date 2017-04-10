# Realtime-processing-for-csitool
A realtime data processing and display visualization plugin for the Linux 802.11n CSI Tool.

# Usage
To use this code, you need the files from https://github.com/dhalperi/linux-80211n-csitool-supplementary.

In netlink:
~~~
gcc log_to_server.c -o log_to_server
sudo ./log_to_server <ip> <port>
~~~

In matlab:
run read_bf_socket.m
