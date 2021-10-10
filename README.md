Make a new statis server
=========

Please change "***" in main.yaml for your data

For test role:
ansible-playbook -vv -i inventory/hosts -o IdentitiesOnly=yes --syntax-check --list-hosts -b -k -u root

Start role:
ansible-playbook -vv -i inventory/hosts -o IdentitiesOnly=yes --list-hosts -b -k -u root
