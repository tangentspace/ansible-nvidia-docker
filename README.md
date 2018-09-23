Ansible NVIDIA Container Runtime Role
=====================================

Install the [NVIDIA container runtime for Docker](https://github.com/NVIDIA/nvidia-docker).

Dependencies
------------

Docker is required, so this role pulls in geerlingguy.docker to install it.

Example Playbook
----------------
```yml
- hosts: gpu-servers
  roles:
     - tangentspace.nvidia_docker
```

License
-------

MIT / BSD
