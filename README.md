# ansible-docker-swarm-playbook
An Ansible playbook to setup and configure a Docker Swarm with Consul as the backend

**Step 1**

Edit inventory file: `swarm_cluster` to suite your environment

**Step 2:**

Run the playbook:

```
ansible-playbook docker-swarm.yml -i swarm_cluster
```

You should now have a swarm up and running.

Read the related blog post: [Docker Swarm with Ansible](http://blog.toast38coza.me/docker-swarm-with-ansible-a-late-swarmweek-entry/)


