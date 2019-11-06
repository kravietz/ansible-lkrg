Linux Kernel Runtime Guard (LKRG) for Ansible
=============================================

Compile and install [Linux Kernel Runtime Guard (LKRG)](https://bitbucket.org/Adam_pi3/lkrg-main/src/master/)

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

```
lkrg_build_dir: "/root/lkrg-main"
lkrg_repo: "https://bitbucket.org/Adam_pi3/lkrg-main.git"
```

Dependencies
------------

Compiler and kernel hearders, both are installed by the role.

Example Playbook
----------------

```
- hosts: servers
  roles:
     - lkrg
```

License
-------

BSD

Author Information
------------------

[Pawel Krawczyk](https://webcookies.org/contact/)
