user_sql
========

Owncloud SQL authentification

This is plugin is heavily based on user_imap, user_pwauth, user_ldap and user_redmine!

Enable it in your Admin -> Apps section and configure your server's details.
Currently, it supports most of postfixadmin's encryption options, except dovecot and saslauthd.
It was tested and developed for a postfixadmin database.

Credits

  * Johan Hendriks provided his user_postfixadmin
  * Ed Wildgoose for fixing possible SQL injection vulnerability
