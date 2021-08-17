# Erigon Ansible
This playbook will create `erigon` user and run erigon node as systemd service.  
By default it builds `stable` branch.  
Edit inventory file `hosts.ini` to set remote machine address and adjust variables to your needs.  

Run playbook
```bash
ansible-playbook -i hosts.ini erigon.yml -l erigon
```