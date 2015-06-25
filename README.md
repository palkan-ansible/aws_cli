AWS CLI
========

Installs AWS CLI and generate default aws config.

Installation
--------------

`ansible-galaxy install palkan.aws_cli`

Role Variables
--------------

There are no defaults, you should define required variables.

| Name                        | Description    |
|-----------------------------|----------------|
| aws_config_user             | User for which config is generated |
| aws_key                     | AWS access key |
| aws_secret                  | AWS secret     |
| aws_region                  | AWS region     |
| aws_session_token           | AWS session token |
| aws_output                  | AWS CLI output format |


Example Playbook
-------------------------

  - hosts: servers
    roles:
       - palkan.aws_cli
