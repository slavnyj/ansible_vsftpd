Role Name
=========

Install FTP server - vsftpd.

Example Playbook
----------------

    - hosts: servers
      gather_facts: no
      become: yes
      roles:
         - vsftpd 

License
-------

BSD

Author Information
------------------

Alexandr Ivanov
