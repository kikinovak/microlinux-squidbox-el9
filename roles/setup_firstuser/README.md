Ansible Role: `setup_firstuser`
===============================

Setup initial non-`root` user account and generate SSH key pair.


Role Variables
--------------

 - `firstuser_login`: login name

 - `firstuser_name`: full name

 - `firstuser_passwd` : password (no default)

 - `firstuser_admin` : add user to `wheel` and `systemd-journal` groups
   (`true`/`false`)


License
-------

BSD


Author Information
------------------

Niki Kovacs <info@microlinux.fr>
