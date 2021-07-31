Role Name
=========

System and configuration with external data

- Fetch user info from github
- Allow git clone access by uploading keys
- Various system configurations

Requirements
------------

None

Role Variables
--------------

Check [defaults](./defaults/main.yml)

Dependencies
------------

None

Usage
-----

```yml
# requirements.yml
roles:
  - name: role-basics
    src: ssh://git@github.com/loic-roux-404/role-basics.git
    version: "configs"
    scm: git
```

```yml
# site.yml
  - hosts: localhost
    roles:
        - { role: username.rolename, x: 42 }
```

License
-------

BSD

Author Information
------------------

[loic-roux-404]
