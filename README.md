# dotfiles-linux
This is my Linux dotfiles setup for bootstrapping an Ubuntu machine

## Add User To Sudo/Admin Group
```
usermod -G sudo $USERNAME
vi /etc/sudoers --> NOPASSWD:ALL
```
## Run Bootstrap Script
```
./bootstrap.sh
```
## Install
```
ansible-playbook setup.yml
```
