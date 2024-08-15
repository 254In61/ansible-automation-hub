# ansible-automation-hub
Repository that has playbooks to configure different objectects in the Ansible Automation Hub
REF: https://console.redhat.com/ansible/automation-hub/repo/validated/infra/ah_configuration/




# How to use

1. Ensure the collection is installed in your dev environment
   $ ansible-galaxy collection install infra.ah_configuration

2. Put the following env variables
export AH_HOST=
export AH_USERNAME=
export AH_PASSWORD=