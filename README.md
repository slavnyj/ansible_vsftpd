Simple playbook for install vsftpd
=========

Install FTP server - vsftpd.

Example Playbook
----------------

    - hosts: servers
      gather_facts: no
      become: yes
      roles:
         - vsftpd 
