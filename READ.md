### Ansibe Playbook for installing Docker on Ubuntu.

1. Update the inventory and add your ip address where docker need to be installed.
2. Run the following command.

##### ansible-playbook -i inventory/hosts docker-module.yaml 