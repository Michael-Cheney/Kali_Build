# Kali Built with Ansible
## Instructions
1. Update repositories
   `sudo apt update`
2. Install Ansible
   `sudo apt install ansible -y`
3. Install Kali updates
   `ansible-playbook upgrade.yaml`
4. Run package install 
   `ansible-playbook setup.yaml`
```