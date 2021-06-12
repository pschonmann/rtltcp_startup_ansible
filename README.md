# rtltcp_startup_ansible
Ansible playbook to setup debian based system with systemd to run rtlsdr at startup

# Instructions to run

1. Copy your ssh public key to /root/.ssh/authorized_keys or user of your choice
2. ansible-playbook -u root -i 192.168.0.10, rtl_sdr_portable.yml
  - -u root
    -  change to your user if you need
  - -i 192.168.0.10,
    - ip of your box. **Comma after ip is needed**
    
