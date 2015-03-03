###read_mac.c
 File to read the interface mac addresses using the IOCTL SIOCGIFHWADDR.
 More snippets at: softlockup. We use getifaddrs() system API to get the name
 of all interfaces. Collected from the internet examples.
 
###Web: 
http://www.softlockup.com

###Git: 
https://github.com/techmuser/linux_user_space.git
 
###Sample output:
```
interface lo family AF_INET address 127.0.0.1 MAC 00:00:00:00:00:00
interface eth0 family AF_INET address 10.100.32.152 MAC XX:YY:zz:4b:46:75
interface lo family AF_INET6 address ::1 MAC 00:00:00:00:00:00
interface eth0 family AF_INET6 address xx80::yy51:zzff:qw4b:uu75%eth0 MAC XX:YY:ZZ:4b:46:75
```
