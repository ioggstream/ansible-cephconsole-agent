Ceph Monitor Agent
==================

Install this on every ceph-mon and ceph-osd so they can be attached to monitor

Requirements
------------

Ansible 1.9+

Role Variables
--------------

cephconsole_host - the fqdn of the ceph  console

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ioggstream.cephconsole-agent, cephconsole_host: ceph-monitoring.example.com }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
