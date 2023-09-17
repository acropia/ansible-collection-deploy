# Ansible Collection - acropia.deploy

The Ansible Collections called `deploy` should host a generic toolkit of roles
to be used in playbooks. No company/implementation specific content should be in
this `deploy` role. If specifc content is requried, that should be placed in the
`deploy_content` role, like:

- ansible - Inventory role
- deploy - Generic Ansible Collection
- deploy_content - Specifc Ansible Collection




## Roles
- mariadb_server_deploy
- zabbix_repo_deploy
