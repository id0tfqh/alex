Role Name
=========

Please change "***" in main.yaml for your data

For test role:
ansible-playbook -vv -i inventory/hosts staric-playbook.yaml -o IdentitiesOnly=yes --syntax-check --list-hosts -b -k -u root

Start role:
ansible-playbook -vv -i inventory/hosts staric-playbook.yaml -o IdentitiesOnly=yes --list-hosts -b -k -u root
