These Ansible playbooks will configure a Raspberry Pi Model A+ for use with the PiTFT hat.

We assume the Pi has been connected to the network manually. It is possible to run all setup commands on a Model B+ or Pi2 and switch SD card afterwards.

# Running
Make sure the target IP in your hosts file is correct and run Ansible:
```
ansible-playbook --ask-pass --ask-sudo-pass -i hosts playbooks/gps.yml
```
