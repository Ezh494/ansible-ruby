## Installation
# Add servers and identity in the inventory - local
* .\inventories\local\hosts

# Write vault password in passfile
* .\pass

# Change application settings
* In the playbook.yml you can change all important variables application

# Start playbook
* ansible-galaxy install -r requirements.yml
* ansible-galaxy collection install -r requirements.yml
* ansible-playbook playbook.yml --vault-id prod@pass