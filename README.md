
$ cd /tmp/ && yum install git -y && git clone https://github.com/telehooot/ovpn && cd OpenVPN-AS-Unlimited/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh

