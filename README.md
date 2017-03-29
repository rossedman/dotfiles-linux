# dotfiles-linux
This is my Linux dotfiles setup for bootstrapping an Ubuntu machine

## Add User To Sudo/Admin Group
```
usermod -G sudo $USERNAME
vi /etc/sudoers --> NOPASSWD:ALL
```

## Install
```
./bootstrap.sh
ansible-playbook setup.yml
cd /tmp && ./google-cloud-sdk/install.sh
gcloud components install kubectl
```
