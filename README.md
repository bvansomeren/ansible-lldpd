bvansomeren.lldpd
=========

Installs LLDP on versions of Linux and FreeBSD. You probably want to learn why here: https://en.wikipedia.org/wiki/Link_Layer_Discovery_Protocol
There is no real configuration required. By default this will emit the server name to the switches

Requirements
------------

Pretty much none. Only useful for hardware deployments

Role Variables
--------------

None at this point

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

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
