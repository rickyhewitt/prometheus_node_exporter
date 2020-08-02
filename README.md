Role Name
=========

An Ansible role that installs Prometheus Node Exporter on Ubuntu/Debian/Redhat-based machines with systemd.

Role Variables
--------------

prometheus_node_exporter_version (string) (default: "1.0.1")

Example Playbook
----------------

- hosts: all
  roles:
    - role: rickyhewitt.prometheus-node-exporter
      prometheus_node_exporter_version: 1.0.1

License
-------

GNU LGPL-3.0-only

Author Information
------------------
Ricky Hewitt <contact@rickyhewitt.dev> <http://rickyhewitt.dev>
