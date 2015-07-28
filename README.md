Ansible Role: Composer
=======================

[![Build Status](https://travis-ci.org/heskethm/ansible-role-composer.svg)](https://travis-ci.org/heskethm/ansible-role-composer)

Ansible role for installing Composer, the PHP dependency manager.

Installation
------------

```
$ ansible-galaxy install heskethm.composer
```

Role Variables
--------------
All available variables and default values are listed below. You may override these in your Playbook, `group_vars`, command line etc.

```yml
composer_ppa: "ppa:duggan/composer"
```

The Personal Package Archive (PPA) to install from via apt-get.

Dependencies
------------

None

Example Playbook
----------------

```yml
- hosts: web
  roles:
     - { role: heskethm.composer }
```

Author
------------------

* Web: [markhesketh.co.uk](http://www.markhesketh.co.uk/)
* Email: [contact@markhesketh.co.uk](mailto:contact@markhesketh.co.uk)
* Twitter: [twitter.com/markyhesketh](http://www.twitter.com/markyhesketh/)
* Github: [github.com/heskethm](http://www.github.com/heskethm/)

License
-------

[MIT](http://opensource.org/licenses/MIT)