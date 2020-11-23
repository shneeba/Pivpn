# Pi Tor

This is a list of commands used to setup a raspberry pi zero with ethernet header

```
ifconfig wlan0 up
ip addr
iwlist wlan0 scan
iwconfig wlan0 essid Nizzle key s:calmtomato045
ip addr
dhclient wlan0
raspi-config
ip addr
ping 8.8.8.8
apt-get update
ipip addr
ip addr
reboot now
cd /var/log/
grep 'enc28j' *
reboot now
raspi-config
cd /etc/net
cd /etc/network
ls -l
more interfaces
cd interfaces
cd interfaces.d/
ls -l
cd ..
ls- l
ls -l
cd if-up.d/
ls -l
cd ..
ls -l
grep -r 'dhcp'
cd /etc/
vi /etc/dhcpcd.conf
service network restart
service networking restart
ip addr
ip addr
reboot now
apt-get install hostapd
systemctl umask hostapd
systemctl unmask hostapd
systemctl enable hostapd
apt-get install dnsmasq
DEBIAN_FRONTEND=noninteractive apt install -y netfilter-persistent iptables-persistent
vi /etc/dhcpcd.conf
vi /etc/dhcpcd.conf
raspi-config
ifquery
ifquery --help
ifconfig
ifdown wlan0
ifdown eth0
networkctl
if
ifconfig
ifdown --help
ifdown -i
ifdown -a
ip addr
ping 8.8.8.8
ip link set wlan0 down
ip addr
vi /etc/dhcpcd.conf
vi /etc/dhcpcd.conf
vi /etc/dhcpcd.conf
vi /etc/dhcpcd.conf
vi /etc/sysctl.d/routed-ap.conf
iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE
netfilter-persistent save
vm /etc/dnsmasq.conf dnsmasq.conf.orig
mv /etc/dnsmasq.conf dnsmasq.conf.orig
vi /etc/dnsmasq.conf
rfkill unblock wlan
vi /etc/hostapd/hostapd.conf
reboot now
ip link set wlan0 up
ip addr
tail -100f /var/log/messages
ip link set wlan0 up
vi /etc/hostapd/hostapd.conf
service dhcpd start
grep dhcp /var/log/syslog
grep 'dhcp' /var/log/syslog
grep 10 /var/log/syslog
grep
grep "10" /var/log/messages
cd /var/log/
ls -l
ls -lart
tail -100f messages
tail -100f syslog
service hostapd stop
tail -100f syslog
ls -l
ls -lart
tail -100f daemon.log
vi /etc/hostapd/hostapd.conf
reboot now
vi /etc/dnsmasq.conf
service dnsmasq status
service dnsmasq start
service dnsmasq status
tail -100f /var/log/syslog
reboot now
ls -l
ls -lart
tail -100f auth.log
ls -l
ls -lart
tail -100f syslog
iptables -L
iptables -t nat -A  POSTROUTING -o eth0 -j MASQUERADE
iptables -L
cd /etc/iptables/
ls -l
more rules.v4
more /etc/sysctl.d/routed-ap.conf
more /etc/sysctl.d/routed-ap.conf
ping google.com
route -n
more /etc/iptables/rules.v4
netstat -r
more /etc/hostapd/hostapd.conf
cd /etc/hostapd/
ls -l
more ifupdown.sh
./ifupdown.sh
ip addr
reboot now
reboot now
vi /etc/dnsmasq.conf
service dnsmasq restart
reboot now
ls -l
vi wlanroute.sh
vi wlanroute.sh
chmod 755 wlanroute.sh
./wlanroute.sh
reboot now
cd /var/log/
ls -l
ls -lart
tail -10f syslog
netstat -an
netstat -an | grep ssh
service sshd status
apt-install sshd
apt-get install sshd
apt-get install ssh
apt-get --help
apt-get search
apt-get list
apt-get install sshd
service sshd status
raspi-config
netstat -anm
netstat -an
apt-get install openvpn
cd /etc/op
cd /etc/openvpn/
wget https://downloads.nordcdn.com/configs/archives/servers/ovpn.zip
apt-get install unzip
unzip ovpn.zip
rm ovpn.zip
cd /etc/openvpn/ovpn_tcp/
ls -l
openvpn uk1749.nordvpn.com.tcp.ovpn
screen
apt-get install screen
screen -S openvpn
screen -r openvpn
ping 8.8.8.8
cd ~
curl icanhazip.com
ip addr
route -n
traceroute google.com
iptables -L
more /etc/iptables/rules.v4
cd /home/pi/
ls -l
more wlanroute.sh
iptables -L
iptables --help
more wlanroute.sh
service networking restart
curl icanhazip.com
reboot now
ls -l
ls -l
ls -l
ls -l | grep uk
openvpn
openvpn uk792.nordvpn.com.tcp.ovpn
iptables -L
cd /home/pi/
ls -l
./wlanroute.sh
reboot now
locate openvpn
apt-get install mlocate
updatedb
locate openvpn
cd /etc/openvpn/
ls -l
cd ovpn_tcp/
ls -l
top
screen -r
screen -r openvpn
screen -S openvpn
screen -r
screen -r openvpn
screen -S openvpn
screen -r openvpn
screen -r openvpn
screen -r openvpn
screen -S openvpn
curl icanhazip.com
route -n
screen -r openvpn
route -n
ping google.com
more wlanroute.sh
cp wlanroute.sh wlanroute_totunnel.sh
vi wlanroute_totunnel.sh
ip addr
vi wlanroute_totunnel.sh
./wlanroute_totunnel.sh
route -n
cd /etc/openvpn/ovpn_tcp/
ls -l
openvpn uk1082.nordvpn.com.tcp.ovpn
openvpn uk1082.nordvpn.com.tcp.ovpn
screen -r openvpn
apt-get install tor
vi /etc/tor/torrc
service tor status
service tor start
service tor status
curl icanhazip.com
service tor stop
curl icanhazip.com
service tor start
iptables -t nat -A PREROUTING -i wlan0 -p tcp --dport 22 -j REDIRECT --to-ports 22
iptables -t nat -A PREROUTING -i wlan0 -p udp --dport 53 -j REDIRECT --to-ports 53
iptables -t nat -A PREROUTING -i wlan0 -p tcp --syn -j REDIRECT --to-ports 9040
sh -c iptables-save > /etc/iptables/rules.v4
service tor restart
curl icanhazip.com
ping google.com
curl icanhazip.com
service tor status
service tor status
ping google.com
ping google.com
curl icanhazip.com
service tor restart
curl icanhazip.com
cd /var/log/
ls -l
cd tor/
ls -l
tail -100f notices.log
ping google.com
curl icanhazip.com
ip addr
tail -100f notices.log
route -n
iptables -t nat -A PREROUTING -i tun0 -p tcp --dport 22 -j REDIRECT --to-ports 22
iptables -t nat -A PREROUTING -i tun0 -p udp --dport 53 -j REDIRECT --to-ports 53
iptables -t nat -A PREROUTING -i tun0 -p tcp --syn -j REDIRECT --to-ports 9040
sh -c iptables-save > /etc/iptables/rules.v4
ping google.com
curl icanhazip.com
reboot now
./wlanroute_totunnel.sh
screen -S openvpn
service tor status
service tor stop
./wlanroute_totunnel.sh
history
iptables-restore
more /etc/iptables/rules.v4
iptables-restore --help
iptables-restore --ipv4
iptables-restore --ipv4 -v
iptables-restore < /etc/iptables/rules.v4
more /etc/iptables/rules.v4
cd /etc/iptables/
ls -l
more rules.v6
more rules.v4
vi rules.v4
reboot now
cd /etc/openvpn/
openvpn ovpn_tcp/uk1082.nordvpn.com.tcp.ovpn
openvpn /etc/openvpn/ovpn_tcp/uk1083.nordvpn.com.tcp.ovpn
openvpn /etc/openvpn/ovpn_tcp/uk1083.nordvpn.com.tcp.ovpn
service tor status
service tor stop
openvpn /etc/openvpn/ovpn_tcp/uk1083.nordvpn.com.tcp.ovpn
vi /etc/iptables/rules.v4
reboot now
screen -S openvpn
service tor stop
apt-get remove tor
./wlanroute_totunnel.sh
service networking restart
cd /etc/openvpn/ovpn_tcp/
openvpn uk1802
openvpn uk1802.nordvpn.com.tcp.ovpn
openvpn uk1802.nordvpn.com.tcp.ovpn
reboot now
openvpn /etc/openvpn/ovpn_tcp/uk950.nordvpn.com.tcp.ovpn
openvpn /etc/openvpn/ovpn_tcp/uk950.nordvpn.com.tcp.ovpn
ls -l
cd /etc/openvpn/
ls -l
mkdir tunnels
cd tunnels/
cd ../ovpn_tcp/
ls -l
more al17.nordvpn.com.tcp.ovpn
ls -l
cp nl* ../tunnels/.
cd ../tunnels/
ls -l
vi n1783
vi nl783
ls -l
vi nl783.nordvpn.com.tcp.ovpn
vi auth
chmod 400 auth
ls -l
openvpn nl783.nordvpn.com.tcp.ovpn
screen -S openvpn
curl icanhazip.com
./wlanroute_totunnel.sh
service firewalld status
vi /etc/iptables/rules.v4
route -n
top
apt-get install glances
glances
top
glances
top
glances
ls -l
screen -r openvpn
cd /etc/openvpn/tunnels/
ls -l
systemctl enable openvpn@nl783.nordvpn.com.tcp.ovpn
reboot now
systemctl disableenable openvpn@nl783.nordvpn.com.tcp.ovpn
systemctl disable openvpn@nl783.nordvpn.com.tcp.ovpn
systemctl enable openvpn@/tunnles/nl783.nordvpn.com.tcp.ovpn
systemctl enable openvpn@tunnles/nl783.nordvpn.com.tcp.ovpn
systemctl enable openvpn@tunnles\/nl783.nordvpn.com.tcp.ovpn
cd /etc/openvpn/
ls -l
mv tunnels/nl783.nordvpn.com.tcp.ovpn.conf .
cd tunnels/
ls -l
mv nl783.nordvpn.com.tcp.ovpn.conf ../
df -h
ls -l
mv nl783.nordvpn.com.tcp.ovpn ../nl783.nordvpn.com.tcp.ovpn
ls -l
cd ..
ls -l
systemctl enable openvpn@nl783.nordvpn.com.tcp.ovpn
mv tunnels/auth .
ls -l
reboot now
tail -10f /var/log/messages
tail -10f /var/log/syslog
cd /etc/openvpn/
ls -l
openvpn nl783.nordvpn.com.tcp.ovpn
openvpn nl783.nordvpn.com.tcp.ovpn
systemctl disable openvpn@nl783.nordvpn.com.tcp.ovpn
screen -S openvpn
ping 8.8.8.8
curl icanhazip.com
cd /home/pi/
ls -l
./wlanroute_totunnel.sh
service networking restart
iptables -F
more wlanroute_totunnel.sh
ls -l
./wlanroute.sh
ls -l
vi /etc/default/openvpn
cd /etc/openvpn/
ls -l
vi /etc/default/openvpn
systemctl daemon-reload
reboot now
openvpn nl783.nordvpn.com.tcp.ovpn
tail -100f /var/log/messages
tail -100f /var/log/syslog
ping 8.8.8.8
curl icanhazip.com
grep openvpn /var/log/syslog
grep "openvpn" /var/log/syslog
cd /var/log/
ls -l
more syslog
ls -l
rm syslog
reboot now
./wlanroute_totunnel.sh
curl icanhazip.com
systemcty
systemctt
systemctl
openvpn nl783.nordvpn.com.tcp.ovpn
cd /etc/openvpn
openvpn nl783.nordvpn.com.tcp.ovpn
curl icanhazip.com
systemctl disable openvpn@nl783.nordvpn.com.tcp.ovpn
tail -100f /var/log/syslog
vi /var/log/syslog
cd /etc/openvpn/
ls -l
history | grep vi
vi /etc/default/openvpn
systemctl enable openvpn@nl783.nordvpn.com.tcp.ovpn
reboot now
systemctl status openvpn@nl783.nordvpn.com.tcp.ovpn
cd /etc/openvpn/
ls -l
cp nl783.nordvpn.com.tcp.ovpn nl783.nordvpn.com.tcp.ovpn.conf
reboot now
ssh 192.168.10.200
route -h
route -n
more /etc/hostapd/hostapd.conf
reboot now
```
