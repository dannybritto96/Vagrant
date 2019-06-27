# Create a Ubuntu Instance and deploy MySQL in it

- Creates an Ubuntu 18.04 VM on VirtualBox.
- Using Shell provisioner to install Python 2 and PIP for Ansible.
- Using Ansible Local provisioner to call playbook.yml which installs and configures MySQL in the instance.

The VM will be available on 192.168.12.10. This can be changed in the Vagrantfile.
