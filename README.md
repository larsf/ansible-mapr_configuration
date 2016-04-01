mapr_configuration
=========

Configure a MapR cluster.

Requirements
------------


Role Variables
--------------

```
mapr_disks: [ "/dev/xvdf", "/dev/xvdg" ]
java_home: /etc/alternatives/java_sdk
cluster_name: mapr.yourcompany.com
metrics_user: maprmetrics
metrics_password: mapr
metrics_host: 1.2.3.4
secure_cluster: false
mapr_subnets: 1.2.3.0/24
```

Dependencies
------------



Example Playbook
----------------

```
- hosts: all
  roles:
    - mapr_configuration
```

License
-------

MIT

Author Information
------------------

Vince Gonzalez
