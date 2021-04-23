# Ansible playbooks for galera cluster (Ubuntu 20.04) 

```
# Step 0 
Install ansible on your local system 

# Step 1 - Adjust your ip's in 
inventory 

# Step 2 - Connect to all nodes once as root with key and agree to host-key 
ssh root@<ip1>
eval $(ssh-agent)
ssh-add 

# Step 3 - Execute scripts 
ansible-playbook galeracluster.yml 
ansible-playbook maxscale.yml
```
