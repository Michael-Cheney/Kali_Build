# Kali Built with Ansible
## Instructions
1. Update repositories

   `sudo apt update`
2. Install Ansible

   `sudo apt install ansible -y`
3. Clone this repo

   `git clone https://github.com/Michael-Cheney/Kali_Build.git`
4. Install Kali updates

   `ansible-playbook Kali_Build/upgrade.yaml`
5. Run package install 

   `ansible-playbook Kali_Build/setup.yaml`

## Todo
* Add PowerLine setup
* Add Neofetch to packages
* Add tmux config