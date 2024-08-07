To run the playbook:

ansible-playbook playbooks/globex.yml -e ACTION=create -i inventories/inventory.template


Remove workload
ansible-playbook playbooks/ocp4_workload_cloud_architecture_workshop.yml -e ACTION=remove