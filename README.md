ansible-lldpd
=========
[![Build Status](https://travis-ci.org/CSCfi/ansible-lldpd.svg?branch=master)](https://travis-ci.org/CSCfi/ansible-lldpd)

Installs LLDP on versions of Linux and FreeBSD. You probably want to learn why here: https://en.wikipedia.org/wiki/Link_Layer_Discovery_Protocol
There is no real configuration required. By default this will emit the server name to the switches

Requirements
------------

Pretty much none. Only useful for hardware deployments

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

Nada

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: bvansomeren.lldpd }

License
-------

BSD

Author Information
------------------

Missing something? Feel free to open an issue with your suggestions or a PR.
Thanks!
