Debian-Curl-HTTP/2
==================

command line tool and library for transferring data with URLs with http/2 support

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

curl.version: 7.54.0

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-curl-http2, curl.version: 7.54.0 }

Tasks
-----

  - Install [nghttp2](https://nghttp2.org/) library
  - Install [Curl](https://curl.haxx.se/) utility

License
-------

BSD
