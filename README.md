# Prometheus with Grafana using Ansible
Using this template, we will configure prometheus, node_exporter, alertmanager and Grafana.

## Getting Started

Step 1: Update ip address of instances in inventory file.

Step 2: Update user in ansible.cfg if needed

Step 3: Run ansible command to setup prometheus, node_exporter, alertmanager and Grafana services

**Ansible command:** 
```
ansible-playbook playbook.yml
```

When everything is ready, we verify that Grafana is accessible on port 3000 which is the default port of Grafana.
Go to http://(grafanaIp):3000 Replace (grafanIp) with your IP.
Enter the username “admin” and password “admin”. Click Log In
