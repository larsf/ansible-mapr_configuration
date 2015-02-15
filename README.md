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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
