ntp-svr
=======

This role configures an NTP client on Ubuntu.

Requirements
------------

N/A

Role Variables
--------------

The information illustrated below should be provided in order to correctly configure the NTP server. The servers list is a sequence of one or more NTP servers from which the local server will get its time reference. The network list is a sequence of networks in the form network/prefix to which the local server will broadcast.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: servers
      vars:
        ntp:
          servers:
            - 192.168.0.10
            - cuckoo.example.local
      roles:
         - ntp-cli

License
-------

MIT

Author Information
------------------

Under construction...
