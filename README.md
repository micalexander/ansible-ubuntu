## Ansible Ubuntu

### Prerequisite
- Install [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
- Have an ubuntu server with a user already created

### Usage
1. Clone this repo:<br /> `git clone https://github.com/micalexander/ansible-ubuntu.git`
2. Change directory into the reop:<br /> `cd ansible-ubuntu/`
3. Install the ansible role requirements<br /> `ansible-galaxy install -r requirements.yml`
4. Run the ansible playbook passing in the ip address of the host to provision where [ip|hostname] is the ip or hostname of the ubuntu server:<br /> `ansible-playbook ubuntu.yml -kK -i "[ip|hostname],"`

