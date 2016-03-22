ansible-role-idmapd
===================
This is very simply role to manage /etc/idmapd.conf. Written as a separate module so it can be applied easily with other modules.

Requirements
------------
Written to work as a standalone role. Tested with ansible 1.9.4. 

Role Variables
--------------
```
idmapd_enabled (default false) - for automation purposes simple switch to disable/enable the role
idmapd_domain (default none)   - NFSv4 domain name
```

Dependencies
------------
Written to work as a standalone role. Tested with ansible 1.9.4.

Example Playbook
----------------
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-idmapd }

License
-------
Apache License version 2.0

Author Information
------------------
https://github.com/mhakala
