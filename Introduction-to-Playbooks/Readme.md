##
update yum repo
1. ansible -i inventory multi -b -B 3600 -P 0 -a "yum -y update"
2. ansible -i inventory  multi -b -a "tail /var/log/messages"
