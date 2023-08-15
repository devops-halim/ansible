1. ansible multi -i inventory -a "hostname" -f 1
2. ansible multi -i inventory -a "df -h" 
3. ansible multi -i inventory -a "pwd"
4. ansible multi -i inventory -a "date"
5. ansible multi -i inventory -a "cat /etc/os-release"
6. ansible ubuntu -i inventory  -m setup
7. ansible -i inventory multi -b -m yum -a "name=ntp state=present"
8. ansible -i inventory multi -K -m yum -a "name=ntp state=present"
9. ansible -i inventory multi -m service -a "name=ntpd state=started enabled=yes"
10. ansible-doc service/apt/yum 
