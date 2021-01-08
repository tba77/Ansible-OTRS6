# Ansible-OTRS6
Installation and configuration of OTRS6 on Centos7.9

# group_vars and inventory

You have to update hosts file and group_vars/all with your informations
- ntp_sever_ip : your NTP server IP or domain name
 - ntp_dir : should be /etc/ or /etc/ntp
- mysql_password : this is the password that will be set for MySQL root user

# Usage

`ansible-playbook -i hosts site.yml --extra-vars "remote_host=YOUR_HOST"`


