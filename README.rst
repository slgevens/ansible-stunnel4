Ansible role for stunnel4
###########################
.. sectnum::

Context
==========

A role to use stunnel4 with Ansible

Example Playbook
===================
::

   stunnel_chroot: /var/lib/stunnel4/
   
   stunnel_uid: stunnel4
   stunnel_gid: stunnel4
   
   stunnel_pid: /stunnel.pid
   
   stunnel_delay: 'no'

   stunnel_log: True
   
   stunnel_cert: /etc/stunnel/stunnel.pem
   
   #stunnel_client: 'yes'
   
   stunnel_services:
     - { name: test, accept: '192.168.2.2:565' connect: '127.0.0.1:444' }

License
============

MIT_

.. _MIT: LICENSE

Author
=======

Evens SOLIGNAC - evenssolignac@live.fr
