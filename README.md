# EVE-NG HSRP example configuration with Ansible

## Eve_NG topology is stored in eveng/ directory

There are couple of ways to run this plabyook:
- single command:

	ansible-playbook hsrp_final.yml
- dual command execution:

1. ansible-playbook basic_config.yml
2. ansible-playbook hsrp_config.yml
