# Automating Multi-node Kubernetes Cluster Deployment on AWS with Ansible

Implementation of the automated K8S cluster setup as described here : https://akanksha77.medium.com/automate-kubernetes-cluster-over-aws-using-ansible-3a1b3f78cfee 

Some modifications were applied:
- Automated ECS2 keypair generation
- Automated VPC creation
- Automated Internet Gateway creation
- Added necessary Route table associations

<br>
Additionally, these Ansible modules needs to be installed:

```
ansible-galaxy collection install amazon.aws
ansible-galaxy collection install community.aws
```