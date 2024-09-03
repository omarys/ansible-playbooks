# Fedora Workstation

This is an opinionated playbook to setup a Fedora 40 workstation with everything you need to start developing on Fedora Linux.

## Quick Setup

Follow these steps to install Ansible, checkout the Fedora Workstation repo, and run the playbook:

```bash
sudo dnf install ansible -y
git clone
cd fedora-workstation
ansible-playbook setup_workstation.yml -e "local_user=yourusername local_user_email=you@example.com" --become -K
```

For further customization, edit `vars/vars.yml` to fit your needs.
