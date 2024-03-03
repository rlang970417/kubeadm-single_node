# kubeadm-single_node

This repository compliments [*Azure Arc-Enabled Kubernetes and Servers*](https://link.springer.com/book/10.1007/978-1-4842-7768-3) by Steve Buchanan (Apress, 2021).

Download the files as a zip using the green button, or clone the repository to your machine using Git.

## Usage
```bash
ansible-playbook -i hosts site.yml
```

## Notes

This repository is an Ansible playbook to deploy a Single Node Kubernetes cluster to Ubuntu Bionic (LTS).
You will run into Docker versioning issues if using a later release of Ubuntu.
This playbook is based off of setup guidance from the book and is meant to speed up the process of environment provisioning.
Edit the provided hosts inventory file to match your target environment.

## References

See the link for book details

https://link.springer.com/book/10.1007/978-1-4842-7768-3
