# Ansible Role: ericsysmin.docker.docker

Documentation can be found here: <https://ericsysmin.github.io/ansible-collection-docker/collections/ericsysmin/docker/docker_role.html>

## Role Summary

This role provides the following:

- Installation of Docker following Docker-Engine install procedures as documented by Docker.
- It will manage kernel versions as well, verifying the that the correct kernel for Docker support is installed.

## Requirements

This role requires Ansible 2.9 or higher. Requirements are listed in the metadata file.

## Example Playbooks

Install docker to the hosts with basic defaults. This does not install devicemapper, or configure the server for production. This just simply installs docker and gets it running. Compare this to `apt install docker-ce` or `yum install docker-ce`.

```yaml
- hosts: servers
  roles:
    - role: ericsysmin.docker.docker
```

Install docker with devicemapper. Please note, this will create a new LVM on /dev/sda3, please do not use a block device already in use. This is the recommended production deployment on RHEL/CentOS/Fedora systems.

```yaml
- hosts: servers
  roles:
    - role: ericsysmin.docker.docker
      docker_storage_driver: devicemapper
      docker_block_device: /dev/sda3
```

Install docker with AUFS. This is recommended for production deployment on Ubuntu systems.

```yaml
- hosts: servers
  roles:
    - role: ericsysmin.docker.docker
      docker_storage_driver: aufs
```

## License

MIT

## Author Information

[ericsysmin](https://ericsysmin.com)
