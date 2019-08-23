#To test from your End

Prerequisites:
1. Get a Centos 7 server
2. Install Ansible

Test the Ansible playbook
1. checkout this repo into your server.
2. Go to nginx/Assignment folder
3. Execute 'ansible-playbook -vvv main.yml'

Validations:
1. On the browser - http://<ip or domain>/xzy --> Display the nginx home page
2. On the browser - http://<ip or domain>/zzyx --> Display the nginx home page
3. On the browser - http://<ip or domain>/grafana --> Display the grafana page
