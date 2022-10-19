This is baisc level of ansible repo.

Before we start diving to ansible please ensure ansible and it's dependency is proeprly installed and configured.
(If it's not then visit https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#pip-install and follow the steps carefully.)

These all playbooks will be run in localhost, if you want to run on other system then you can specify your system in /etc/ansible/hosts file

Here you will see how to tag a specific tasks while running. (ansible-tags.yaml)
and how you can include various playbooks in one main playbook.(ansible-include)