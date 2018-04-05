## openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible. Forked from [Nyr's installer](https://github.com/Nyr/openvpn-install) as I wanted some DNS options he wasn't willing to add.

Added: Quad9 DNS.

### Installation
Run the script and follow the assistant:

`wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

### I want to run my own VPN but don't have a server for that
You can get a little server for just $5/month at [Linode](https://www.linode.com/?r=785ce81e9fa37c90c73df2d202381459553c58a4).
