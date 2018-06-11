efs Role
=========


Role Variables
--------------

```
# Mount target required if efs_enabled is true
efs_target

efs_enabled: false
efs_dir: /mnt/efs

```

----------------

```
#   requirements.yml
#
#   Example
# - src: https://github.com/ergontech-ansible-roles/efs
#   version: master
#   name: efs
```

License
-------

[MIT](LICENSE)