.. _mmctl_ldap_sync:

mmctl ldap sync
---------------

Synchronize now

Synopsis
~~~~~~~~


Synchronize all LDAP users and groups now.

::

  mmctl ldap sync [flags]

Examples
~~~~~~~~

::

    ldap sync

Options
~~~~~~~

::

  -h, --help                      help for sync
      --include-removed-members   Include members who left or were removed from a group-synced team/channel

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --config-path string           path to the configuration directory. If "$HOME/.mmctl" exists it will take precedence over the default value (default "$XDG_CONFIG_HOME")
      --format string                the format of the command output [plain, json] (default "plain")
      --insecure-sha1-intermediate   allows to use insecure TLS protocols, such as SHA-1
      --insecure-tls-version         allows to use TLS versions 1.0 and 1.1
      --local                        allows communicating with the server through a unix socket
      --strict                       will only run commands if the mmctl version matches the server one

SEE ALSO
~~~~~~~~

* `mmctl ldap <mmctl_ldap.rst>`_ 	 - LDAP related utilities

