Make a new statis server
=========

Please change "***" in main.yaml for your data

For test role:
ansible-playbook -vv -i roles/inventory/hosts common.yaml common.yaml --syntax-check --list-hosts -b -k -u root

Start role:
ansible-playbook -vv -i roles/inventory/hosts common.yaml common.yaml  -b -k -u root
