perl
=========

Installs:
1) perl-doc
2) modules requires to support XS cpan dependencies
3) cpanminus
3) carton

After that you can use carton to deploy your application level dependencies

Example Playbook
----------------

    - hosts: servers
      roles:
         - WebbyLab.perl

License
-------

MIT

Author Information
------------------

WebbyLab (http://webbylab.com)