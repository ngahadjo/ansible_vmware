
# Change one esxi host NTP server using one yml file

ansible-playbook config_esxi_ntp_single.yml

# Change one esxi host NTP server using multiple yml file

ansible-playbook config_esxi_ntp.yml

# Change all esxi host NTP server config using host invetory

ansible-playbook -i esxi_host config_esxi_ntp_hostinventory.yml 
