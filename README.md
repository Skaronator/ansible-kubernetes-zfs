# Ansible Playbook to install Kubernetes and ZFS

This is a playbook to setup my NAS. This playbook is designed to run on a fresh installed Debian 10 system. It'll install ZFS, Docker, Kubernetes and setup the Kubernetes Cluster.

To run this playbook you need to adjust your inventory.yaml to match you machine and then run `ansible-playbook -i inventory.yaml install-linuxserver.yaml`.
