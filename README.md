# Realtime-processing-for-csitool
A realtime data processing and display visualization plugin for the Linux 802.11n CSI Tool.

# Usage
To use this code, you will need all the files from https://github.com/dhalperi/linux-80211n-csitool-supplementary.

In netlink:
~~~
gcc log_to_server.c -o log_to_server
sudo ./log_to_server <ip> <port>
~~~

In matlab:
run read_bf_socket.m

Tips for Matlab version > R2014a: 
We use EraseMode to increase the rendering speed. Starting in R2014b, the EraseMode property has been removed from all graphics objects. https://mathworks.com/help/matlab/graphics_transition/how-do-i-replace-the-erasemode-property.html
