# Configure docker, launch a container using ansible, and update the inventory dynamically.
these script are created to implement Kubernetes Multinode Cluster using Ansible Automation tool.
![multi_node_k8s_cluster_architecture](multi_node_k8s_cluster.gif)

## Steps to implement.
- clone the repository.
```
git clone https://github.com/Adamaya/ansible_projects.git
cd ansible_projects/configure_docker/
```
- run the playbook **configure_docker.yml** to configure docker.
```
ansible-playbook configure_docker.yml
```
- now open the file launch_docker_container/vars/main.yml and enter thee credential of your docker hub account. 
- run the playbook **launch_container.yml** to launch webserver docker container.
```
ansible-playbook launch_container.yml
```
- open the inventory file and check the ip of newly launched container.

## Author
[Adamaya Sharma](https://www.linkedin.com/in/adamaya-sharma/)

