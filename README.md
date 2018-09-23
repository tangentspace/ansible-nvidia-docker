Ansible NVIDIA Container Runtime Role
=====================================

Install the [NVIDIA container runtime for Docker](https://github.com/NVIDIA/nvidia-docker).

Requirements
------------

The container runtime requires Docker and the NVIDIA driver to be installed.

Example Playbook
----------------
```yml
- hosts: gpu-servers
  roles:
    - geerlingguy.docker
    - tangentspace.nvidia_driver
    - tangentspace.nvidia_docker
```

License
-------

MIT / BSD
