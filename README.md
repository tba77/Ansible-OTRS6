# Ansible-OTRS6
Installation and configuration of OTRS6 on Centos7.9

#group_vars and inventory

You have to update hosts file and group_vars/all with your informations
ntp_sever_ip
ntp_dir
mysql_password

# Usage

`ansible-playbook -i hosts site.yml --extra-vars "remote_host=YOUR_HOST"`


