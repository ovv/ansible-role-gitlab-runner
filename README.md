ovv.gitlab-runner
=================

[![Build Status](https://travis-ci.org/ovv/ansible-role-gitlab-runner.svg?branch=master)](https://travis-ci.org/ovv/ansible-role-gitlab-runner)

Ansible role to install a Gitlab CI runner

Installation
------------

To install this roles clone it into your roles directory.

```bash
$ git clone https://github.com/ovv/ansible-role-gitlab-runner.git ovv.gitlab-runner
```

If your playbook already reside inside a git repository you can clone it by using git submodules.

```bash
$ git submodule add -b master https://github.com/ovv/ansible-role-gitlab-runner.git ovv.gitlab-runner
```

Example Playbook
----------------

```yml
- hosts: gitlab-runner
  tags:
    - gitlab-runner
  roles:
    - ovv.gitlab-runner
```

License
-------

MIT
