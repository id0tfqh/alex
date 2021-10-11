Make a new statis server
=========

Please change "***" in main.yaml for your data

For syntax test role:
ansible-playbook -vv -i roles/inventory/hosts common.yaml common.yaml --syntax-check --list-hosts -b -k -u root

For check the work a role:
ansible-playbook -vv -i roles/inventory/hosts common.yaml -C -b -k -u root

Start role:
ansible-playbook -vv -i roles/inventory/hosts common.yaml -b -k -u root
