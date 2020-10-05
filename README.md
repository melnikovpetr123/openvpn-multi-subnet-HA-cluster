# openvpn-multi-subnet-HA-cluster
An example how you can orginize an HA VPN-gateway based on OpenVPN in Google Cloud Platform with supporting dedicated subnet per domain user group (MS AD/FreeIPA)


https://www.howtoforge.com/tutorial/how-to-install-openvpn-server-and-client-with-easy-rsa-3-on-centos-8/
https://www.digitalocean.com/community/tutorials/how-to-set-up-and-configure-an-openvpn-server-on-centos-7
https://openvpn.net/community-resources/using-alternative-authentication-methods/
https://forums.openvpn.net/viewtopic.php?t=13053



1. Create two nodes (master node - the main compute capasity is here; slave node - as a failover, probably is enough to take some small instance). For to have better understanding about OpenVPN performance read these: https://openvpn.net/vpn-server-resources/openvpn-access-server-system-requirements/ and https://community.openvpn.net/openvpn/wiki/Gigabit_Networks_Linux
