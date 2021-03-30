# ansible-k8s

Basic Ansible role To bootstrap a minimal K8S single master cluster using kubeadm. 

The repo contains three roles: 


- k8s_install: responsible for installing containerd and k8s binaries 
- k8s_master: responsbile for creating the k8s cluster
- k8s_worker: responsible for joining workers to k8s cluster
