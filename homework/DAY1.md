### DAY-1 Homework

Start two virtual machines using Vagrant. No additional commands are required, salt-minion is already connected to salt-master.

Master virtual machine:

1. Need to install salt-master and salt-minion.
2. hostname: master
3. private ip: 192.168.56.20

Minion virtual machine:

1. Need to install salt-minion.
2. hostname: minion
3. private ip: 192.168.56.21

Virtual machine configuration:

- Box: ubuntu/focal64
- Memory: 1G
- CPU: 1

Practicing:

- salt-key
- salt
- salt-call
