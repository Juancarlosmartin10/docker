Install RedHat OKD 3.11 on your development box.

This repository is a set of scripts that will allow you easily install the latest version (3.11) of OKD in a single node fashion.  What that means is that all of the services required for OKD to function (master, node, etcd, etc.) will all be installed on a single host.  The script supports a custom hostname which you can provide using the interactive mode.

## Installation

1. Create a VM as explained in https://www.youtube.com/watch?v=ZkFIozGY0IA (this video) by Grant Shipley

2. Clone this repo

```
git clone https://github.com/Juancarlosmartin10/docker.git
```

3.Install Ansible 2.6.5 \n

sudo rpm -iUvh https://releases.ansible.com/ansible/rpm/release/epel-7-x86_64/ansible-2.6.5-1.el7.ans.noarch.rpm


4. Execute the installation script

```
cd installcentos
./install-openshift.sh
