# ansible-docker-installation
docker installation by ansible

ansible-docker-setup/

├── ansible.cfg

├── prepare_env.yml

├── roles/

│   └── prepare_env/

│       ├── defaults/

│       │   └── main.yml

│       ├── tasks/

│       │   └── main.yml

│       └── vars/

│           └── main.yml

# How to run

Run the playbook

```
ansible-playbook prepare_env.yml -i inventory
```
