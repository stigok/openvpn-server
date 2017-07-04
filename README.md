# openvpn-server

> **WORK IN PROGRESS!**

## Setup

    $ git clone $REPO $DEST
    # apt-get install iptables ip6tables openvpn
    # cp -r $DEST/* /
    # cp -r /usr/share/openvpn/easy-rsa /etc/openvpn/
    # cd /etc/openvpn/easy-rsa
    
Now, open up the `vars` file and read it carefully to keep a persistent environment for creating new certs and keys. Specifically, the other files in this repo expects the `KEY_SIZE` to be `4096`.
    
    # source ./vars
    
    
    
    # systemctl restart openvpn
    # systemctl start openvpn
