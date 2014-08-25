osx-git
=======

An Ansible role to setup git on OS X

Requirements
------------

[Homebrew](http://brew.sh/) must be installed.

Role Variables
--------------

These two variables have no default values. You must specify values.

- git_user_name
- git_user_email

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: hnakamur.osx-git,
             git_user_name: "Hiroaki Nakamura", git_user_email: "hnakamur@gmail.com" }

License
-------

MIT

Author Information
------------------

[Hiroaki Nakamura]( http://hnakamur.github.io/ )
