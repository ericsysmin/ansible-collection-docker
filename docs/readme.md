# Installing Docker via Ansible

## Default Docker Install

```yaml
---
- hosts: all
  roles:
    - role: avinetworks.docker
```

## Install Docker w/devicemapper

```yaml
---
- hosts: all
  roles:
    - role: avinetworks.docker
      docker_storage_driver: devicemapper
      docker_block_device: /dev/sda3
```

## Install Docker w/HTTP Proxy Support

```yaml
---
- hosts: all
  roles:
    - role: avinetworks.docker
      docker_http_proxy: http://proxy.example.com:80/
      docker_https_proxy: https://proxy.example.com:443/
```

## Install Docker w/HTTP Proxy Support & without proxy on internal sites

```yaml
---
- hosts: all
  roles:
    - role: avinetworks.docker
      docker_http_proxy: http://proxy.example.com:80/
      docker_https_proxy: https://proxy.example.com:443/
      docker_no_proxy_params: "localhost,127.0.0.0/8,docker-registry.example.com"
```

## Install Docker and customize the storage directory of images and containers

```yaml
---
- hosts: all
  roles:
    - role: avinetworks.docker
      docker_graph: /home/docker
```

## Install/Upgrade Docker. Avoid container downtime during the upgrade of a Docker

```yaml
---
- hosts: all
  roles:
    - role: avinetworks.docker
      docker_live_restore: true
```
