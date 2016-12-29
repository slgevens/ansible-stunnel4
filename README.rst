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
   
   stunnel_client: 'yes'
   
   stunnel_service_name: test
   stunnel_service_accept: '192.168.2.2:565' 
   stunnel_service_connect: '127.0.0.1:444' 
   --- 
   stunnel_service_client: 'yes' or 'no'

License
============

MIT_

.. _MIT: LICENSE

Author
=======

Evens SOLIGNAC - evenssolignac@live.fr
