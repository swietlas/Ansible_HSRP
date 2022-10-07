# EVE-NG HSRP example configuration with Ansible

#### Short summary
Eve-ng topology is stored in **eveng/** directory. I used eve-ng pro version. Please use Python virutal Environments.This was compiled to support ansible 2.9.4 version howerver it also should work with release >= 2.10.x 
Backups are stored in backups/ dir.

#### Please use Python venv
`source venv/bin/activate`

#### How to push configuration with Ansible playbook(s). 
There are two ways to use this demonstration.

- Single command:

    `ansible-playbook hsrp_final.yml`

- dual command execution.

    Configure basic settings using *basic_config.yml* inclugint creating interfaces, assigning IP addresses, adding VLANs and configure Trunk ports.

    `ansible-playbook basic_config.yml`

    Apply HSRP and tracking settings.

    `ansible-playbook hsrp_config.yml`




