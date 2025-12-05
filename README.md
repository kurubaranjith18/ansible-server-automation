# ansible-server-automation

```md
# Ansible Server Automation (DevOps Portfolio)

This project automates server setup using Ansible playbooks and roles.  
It demonstrates configuration management — a key DevOps skill.

---

## 📁 Files Included

| File | Purpose |
|------|---------|
| `inventory.ini` | Target server list |
| `playbook.yml` | Main playbook calling all roles |
| `roles/nginx/` | Installs & configures Nginx |
| `roles/docker/` | Installs Docker Engine |
| `roles/users/` | Adds devops user |

---

## 🚀 How to Run

### Test connection
```sh
ansible -i inventory.ini all -m ping
Run playbook
ansible-playbook -i inventory.ini playbook.yml

