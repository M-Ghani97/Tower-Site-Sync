# AAP_Site_Sync
# Red Hat Ansible Automation Platform 2.2
## Automation Controller - Configuration As Code

The purpose of these files is to provide a method that when the _group_vars/all.yml_ is modified and updated to the repository, this will kick off a job template within SDAIA Ansible Automation Platform automation controller cluster to make the appropriate change, for example, when a project is created at the Active site (Riyadh) the same will be created at Standby DR site (Jeddah).

NOTE: It is recommended to create multiple _yml_ files within the _group_vars_ directory for each type of configuration SDAIA automates, for example, when creating users, _users.yml_

