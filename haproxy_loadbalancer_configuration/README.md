# Configure Reserve Proxy over the EC2 instance in a minute with Ansible
### How implement project
- clone the repository
``` git clone https://https://github.com/Adamaya/ansible_projects.git ```

- go to ansible_projects/haproxy_loadbalancer_configuration folder
``` cd ansible_projects/haproxy_loadbalancer_configuration ```

- modifiy inventory ip's and private key path

- run both configure_loadbalancer.yml and configure_webserver.yml ansible playbook 
```
ansible-playbook configure_loadbalancer.yml
ansible-playbook configure_webserver.yml
```
### How to test
Enter the ip of load balancer in web browser.
```<load_balancer_ip>:5000```

### detailed blog link
[Configure Reserve Proxy over the EC2 instance in a minute with Ansible](https://medium.com/@adamaya.sharma_iot18/configure-haproxy-over-the-ec2-instance-in-a-minute-with-ansible-2cde770d9ebf)
