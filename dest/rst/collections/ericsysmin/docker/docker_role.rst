
.. Document meta

:orphan:

.. |antsibull-internal-nbsp| unicode:: 0xA0
    :trim:

.. meta::
  :antsibull-docs: 2.6.1

.. Anchors

.. _ansible_collections.ericsysmin.docker.docker_role:

.. Title

ericsysmin.docker.docker role -- Ansible role to install and configure Docker
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

.. Collection note

.. note::
    This role is part of the `ericsysmin.docker collection <https://galaxy.ansible.com/ui/repo/published/ericsysmin/docker/>`_ (version 1.0.0).

    It is not included in ``ansible-core``.
    To check whether it is installed, run :code:`ansible-galaxy collection list`.

    To install it use: :code:`ansible-galaxy collection install ericsysmin.docker`.

    To use it in a playbook, specify: :code:`ericsysmin.docker.docker`.

.. contents::
   :local:
   :depth: 2


.. Entry point title

Entry point ``main`` -- Ansible role to install and configure Docker
--------------------------------------------------------------------

.. version_added


.. Deprecated


Synopsis
^^^^^^^^

.. Description

- Installation of Docker following Docker-Engine install procedures as documented by Docker.
- It will manage kernel versions as well, verifying the that the correct kernel for Docker support is installed.

.. Requirements


.. Options

Parameters
^^^^^^^^^^

.. tabularcolumns:: \X{1}{3}\X{2}{3}

.. list-table::
  :width: 100%
  :widths: auto
  :header-rows: 1
  :class: longtable ansible-option-table

  * - Parameter
    - Comments

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_api_cors_header"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_api_cors_header:

      .. rst-class:: ansible-option-title

      **docker_api_cors_header**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_api_cors_header" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set CORS headers in the remote API


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_authorization_plugins"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_authorization_plugins:

      .. rst-class:: ansible-option-title

      **docker_authorization_plugins**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_authorization_plugins" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Authorization plugins to load


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_bip"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_bip:

      .. rst-class:: ansible-option-title

      **docker_bip**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_bip" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Specify network bridge IP


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_block_device"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_block_device:

      .. rst-class:: ansible-option-title

      **docker_block_device**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_block_device" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      The device name used for the storage driver.


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_bridge"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_bridge:

      .. rst-class:: ansible-option-title

      **docker_bridge**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_bridge" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Attach containers to a network bridge


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_cgroup_parent"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_cgroup_parent:

      .. rst-class:: ansible-option-title

      **docker_cgroup_parent**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_cgroup_parent" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set parent cgroup for all containers


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_channel"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_channel:

      .. rst-class:: ansible-option-title

      **docker_channel**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_channel" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      What release channel of Docker to install.


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"stable"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_cluster_advertise"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_cluster_advertise:

      .. rst-class:: ansible-option-title

      **docker_cluster_advertise**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_cluster_advertise" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Address or interface name to advertise


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_cluster_store"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_cluster_store:

      .. rst-class:: ansible-option-title

      **docker_cluster_store**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_cluster_store" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set cluster store options


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_cluster_store_opts"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_cluster_store_opts:

      .. rst-class:: ansible-option-title

      **docker_cluster_store_opts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_cluster_store_opts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Please see dockerd manual for info


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_debug"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_debug:

      .. rst-class:: ansible-option-title

      **docker_debug**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_debug" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable debug mode


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_default_gateway"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_default_gateway:

      .. rst-class:: ansible-option-title

      **docker_default_gateway**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_default_gateway" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Container default gateway IPv4 address


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_default_gateway_v6"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_default_gateway_v6:

      .. rst-class:: ansible-option-title

      **docker_default_gateway_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_default_gateway_v6" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Container default gateway IPv6 address


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_default_runtime"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_default_runtime:

      .. rst-class:: ansible-option-title

      **docker_default_runtime**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_default_runtime" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Default OCI runtime for containers


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_default_ulimits"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_default_ulimits:

      .. rst-class:: ansible-option-title

      **docker_default_ulimits**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_default_ulimits" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Default ulimits for containers


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_disable_legacy_registry"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_disable_legacy_registry:

      .. rst-class:: ansible-option-title

      **docker_disable_legacy_registry**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_disable_legacy_registry" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Disable contacting legacy registries


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_dns"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_dns:

      .. rst-class:: ansible-option-title

      **docker_dns**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_dns" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      DNS server to use


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_dns_opts"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_dns_opts:

      .. rst-class:: ansible-option-title

      **docker_dns_opts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_dns_opts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      DNS options to use


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_dns_search"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_dns_search:

      .. rst-class:: ansible-option-title

      **docker_dns_search**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_dns_search" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      DNS search domains to use


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_edition"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_edition:

      .. rst-class:: ansible-option-title

      **docker_edition**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_edition" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Specifies either ce, or ee version of Docker.


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"ce"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_ee_url"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_ee_url:

      .. rst-class:: ansible-option-title

      **docker_ee_url**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_ee_url" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Docker EE URL from the Docker Store


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_ee_version"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_ee_version:

      .. rst-class:: ansible-option-title

      **docker_ee_version**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_ee_version" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Docker EE version for EE repository


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`17.03`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_exec_opts"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_exec_opts:

      .. rst-class:: ansible-option-title

      **docker_exec_opts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_exec_opts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Runtime execution options


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_exec_root"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_exec_root:

      .. rst-class:: ansible-option-title

      **docker_exec_root**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_exec_root" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Root directory for execution state files


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_fixed_cidr"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_fixed_cidr:

      .. rst-class:: ansible-option-title

      **docker_fixed_cidr**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_fixed_cidr" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      IPv4 subnet for fixed IPs


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_fixed_cidr_v6"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_fixed_cidr_v6:

      .. rst-class:: ansible-option-title

      **docker_fixed_cidr_v6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_fixed_cidr_v6" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      IPv6 subnet for fixed IPs


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_graph"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_graph:

      .. rst-class:: ansible-option-title

      **docker_graph**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_graph" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Root of the Docker runtime


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_group"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_group:

      .. rst-class:: ansible-option-title

      **docker_group**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_group" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Group for the unix socket


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_hosts"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_hosts:

      .. rst-class:: ansible-option-title

      **docker_hosts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_hosts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Daemon socket(s) to connect to


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_http_proxy"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_http_proxy:

      .. rst-class:: ansible-option-title

      **docker_http_proxy**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_http_proxy" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set the Docker service to use HTTP\_PROXY


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_https_proxy"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_https_proxy:

      .. rst-class:: ansible-option-title

      **docker_https_proxy**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_https_proxy" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set the Docker service to use HTTPS\_PROXY


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_icc"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_icc:

      .. rst-class:: ansible-option-title

      **docker_icc**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_icc" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable inter-container communication


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_insecure_registries"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_insecure_registries:

      .. rst-class:: ansible-option-title

      **docker_insecure_registries**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_insecure_registries" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable insecure registry communication


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_ip"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_ip:

      .. rst-class:: ansible-option-title

      **docker_ip**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_ip" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Default IP when binding container ports


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_ip_forward"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_ip_forward:

      .. rst-class:: ansible-option-title

      **docker_ip_forward**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_ip_forward" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable net.ipv4.ip\_forward


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_ip_masq"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_ip_masq:

      .. rst-class:: ansible-option-title

      **docker_ip_masq**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_ip_masq" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable IP masquerading


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_iptables"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_iptables:

      .. rst-class:: ansible-option-title

      **docker_iptables**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_iptables" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable addition of iptables rules


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_ipv6"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_ipv6:

      .. rst-class:: ansible-option-title

      **docker_ipv6**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_ipv6" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable IPv6 networking


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_labels"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_labels:

      .. rst-class:: ansible-option-title

      **docker_labels**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_labels" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set key=value labels to the daemon


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_live_restore"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_live_restore:

      .. rst-class:: ansible-option-title

      **docker_live_restore**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_live_restore" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enables keeping containers alive during daemon downtime


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_log_driver"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_log_driver:

      .. rst-class:: ansible-option-title

      **docker_log_driver**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_log_driver" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Default driver for container logs


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_log_level"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_log_level:

      .. rst-class:: ansible-option-title

      **docker_log_level**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_log_level" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set the logging level


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_log_opts"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_log_opts:

      .. rst-class:: ansible-option-title

      **docker_log_opts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_log_opts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Default log driver options for containers


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_max_concurrent_downloads"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_max_concurrent_downloads:

      .. rst-class:: ansible-option-title

      **docker_max_concurrent_downloads**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_max_concurrent_downloads" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set the max concurrent downloads for each pull


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_max_concurrent_uploads"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_max_concurrent_uploads:

      .. rst-class:: ansible-option-title

      **docker_max_concurrent_uploads**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_max_concurrent_uploads" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set the max concurrent uploads for each push


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_mount_opts"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_mount_opts:

      .. rst-class:: ansible-option-title

      **docker_mount_opts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_mount_opts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      The mount options when mounting filesystems


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_mtu"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_mtu:

      .. rst-class:: ansible-option-title

      **docker_mtu**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_mtu" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set the containers network MTU


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_no_proxy_params"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_no_proxy_params:

      .. rst-class:: ansible-option-title

      **docker_no_proxy_params**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_no_proxy_params" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Do not proxy for Docker service params


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_oom_score_adjust"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_oom_score_adjust:

      .. rst-class:: ansible-option-title

      **docker_oom_score_adjust**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_oom_score_adjust" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set the oom\_score\_adj for the daemon


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_pidfile"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_pidfile:

      .. rst-class:: ansible-option-title

      **docker_pidfile**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_pidfile" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Path to use for daemon PID file


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_raw_logs"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_raw_logs:

      .. rst-class:: ansible-option-title

      **docker_raw_logs**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_raw_logs" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Full timestamps without ANSI coloring


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_registry_mirrors"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_registry_mirrors:

      .. rst-class:: ansible-option-title

      **docker_registry_mirrors**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_registry_mirrors" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Preferred Docker registry mirror


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_repo"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_repo:

      .. rst-class:: ansible-option-title

      **docker_repo**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_repo" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Defines how Ansible manages the repository

      Options are \ :literal:`other`\  and \ :literal:`docker`\ 


      .. rst-class:: ansible-option-line

      :ansible-option-default-bold:`Default:` :ansible-option-default:`"docker"`

      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_runtimes"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_runtimes:

      .. rst-class:: ansible-option-title

      **docker_runtimes**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_runtimes" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Register an additional OCI compatible runtime


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_selinux_enabled"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_selinux_enabled:

      .. rst-class:: ansible-option-title

      **docker_selinux_enabled**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_selinux_enabled" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Enable selinux support


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_storage_driver"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_storage_driver:

      .. rst-class:: ansible-option-title

      **docker_storage_driver**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_storage_driver" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Storage driver to use


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_storage_opts"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_storage_opts:

      .. rst-class:: ansible-option-title

      **docker_storage_opts**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_storage_opts" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Storage driver options


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_swarm_default_advertise_addr"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_swarm_default_advertise_addr:

      .. rst-class:: ansible-option-title

      **docker_swarm_default_advertise_addr**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_swarm_default_advertise_addr" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Set default address or interface for swarm advertised address


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_tls"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_tls:

      .. rst-class:: ansible-option-title

      **docker_tls**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_tls" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Use TLS; implied by –tlsverify


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_tlscacert"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_tlscacert:

      .. rst-class:: ansible-option-title

      **docker_tlscacert**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_tlscacert" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Trust certs signed only by this CA


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_tlscert"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_tlscert:

      .. rst-class:: ansible-option-title

      **docker_tlscert**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_tlscert" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Path to TLS certificate file


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_tlskey"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_tlskey:

      .. rst-class:: ansible-option-title

      **docker_tlskey**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_tlskey" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Path to TLS key file


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_tlsverify"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_tlsverify:

      .. rst-class:: ansible-option-title

      **docker_tlsverify**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_tlsverify" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Use TLS and verify the remote


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_userland_proxy"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_userland_proxy:

      .. rst-class:: ansible-option-title

      **docker_userland_proxy**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_userland_proxy" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      Use userland proxy for loopback traffic


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_userns_remap"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_userns_remap:

      .. rst-class:: ansible-option-title

      **docker_userns_remap**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_userns_remap" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      User/Group setting for user namespaces


      .. raw:: html

        </div>

  * - .. raw:: html

        <div class="ansible-option-cell">
        <div class="ansibleOptionAnchor" id="parameter-main--docker_users"></div>

      .. _ansible_collections.ericsysmin.docker.docker_role__parameter-main__docker_users:

      .. rst-class:: ansible-option-title

      **docker_users**

      .. raw:: html

        <a class="ansibleOptionLink" href="#parameter-main--docker_users" title="Permalink to this option"></a>

      .. ansible-option-type-line::

        :ansible-option-type:`string`




      .. raw:: html

        </div>

    - .. raw:: html

        <div class="ansible-option-cell">

      A list of system users to be added to the docker group (so they can use Docker on the server)


      .. raw:: html

        </div>


.. Attributes


.. Notes


.. Seealso


Authors
^^^^^^^

- Eric Anderson



.. Extra links

Collection links
~~~~~~~~~~~~~~~~

.. ansible-links::

  - title: "Issue Tracker"
    url: "https://github.com/ericsysmin/ansible-collection-docker/issues"
    external: true
  - title: "Repository (Sources)"
    url: "https://github.com/ericsysmin/ansible-collection-docker"
    external: true


.. Parsing errors

