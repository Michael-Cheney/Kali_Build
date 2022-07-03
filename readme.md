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

* wget https://github.com/ropnop/kerbrute/releases/download/v1.0.3/kerbrute_linux_amd64
* to /usr/local/sbin

* sudo gunzip /usr/share/wordlists/rockyou.txt.gz
* mkdir /home/kali/share/
* wget https://github.com/carlospolop/PEASS-ng/releases/download/20220626/winPEASany.exe

* Translation Plugin
https://addons.mozilla.org/firefox/addon/traduzir-paginas-web/

* BurpSuite

* SQLmap
cd \opt
sudo git clone --depth 1 https://github.com/sqlmapproject/sqlmap.git sqlmap-dev

* Install PowerShell 
`sudo apt -y install powershell`