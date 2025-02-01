Ansible Role: `configure_locale`
================================

Set parameters for:

- System locale

- Console keyboard layout


Role Variables
--------------

- `locale`: defaults to `fr_FR.UTF-8`. Other possible values are `fr_BE.UTF-8`,
  `de_AT.UTF-8`, `en_US.UTF-8`, etc. Use `localectl list-locales` to display
  available locales.

- `console_keymap`: defaults to `ch-fr`. Other possible values are `fr`, `be`,
  `de`, `us`, etc. Use `localectl list-keymaps` to display available console
  keymaps.


License
-------

BSD


Author Information
------------------

Niki Kovacs <info@microlinux.fr>
