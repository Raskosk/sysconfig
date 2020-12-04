Role Name
=========

Basic System Configuration
 - /etc/environment

Requirements
------------

None

Role Variables
--------------

http_proxy
https_proxy
no_proxy

Dependencies
------------

None 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
      - http_proxy: "http://example.com:80"
      - https_proxy: "http://example.com:80"
      - no_proxy: "127.0.0.1, localhost"
      roles:
         - raskosk.sysconfig

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
