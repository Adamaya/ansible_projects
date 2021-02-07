# Configure k8s Multinode Cluster using Ansible Automation tool.
these script are created to implement Kubernetes Multinode Cluster using Ansible Automation tool.

## Steps to implement.
- clone the repository.
```
git clone https://github.com/Adamaya/ansible_projects.git
cd ansible_projects/provision-k8s-cluster/
```
- enter the ip of your master and slave node in inventory.
- copy the private key and give the required permission to the key.
- change the private key name in ansible.cfg
- run the playbook **configure-k8s-cluster.yml**.
```
ansible-playbook configure-k8s-cluster.yml
```
- ssh into k8s master node and run the following command to see the cluster status.
```
kubectl get nodes
```
## Author
[Adamaya Sharma](https://www.linkedin.com/in/adamaya-sharma/)
