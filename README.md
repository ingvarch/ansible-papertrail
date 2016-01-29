# Ansible Role: papertrail

[![Build Status](https://travis-ci.org/ingvarch/ansible-papertrail.svg?branch=master)](https://travis-ci.org/ingvarch/ansible-papertrail)


## Use

```
  roles:
    - role: ansible-papertrail
      papertrail:
        logs:
          - { path: /var/log/auth.log, comment: 'Auth logs'  }
          - { path: /var/log/nginx/*.log, comment: 'All nginx logs'  }
```
