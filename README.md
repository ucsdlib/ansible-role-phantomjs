PhantomJS
=========

Installs [PhantomJS](http://phantomjs.org/) via provided tar for linux x86/64.

Requirements
------------

No external requirements.

Role Variables
--------------

* `phantomjs_version`: Desired version to install (2.1.1)
* `phantomjs_install_dir`: Location to install (/opt)
* `phantomjs_download_dir`: Location to install (/tmp)

Dependencies
------------

No external roles are required.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ucsdlib.phantomjs, phantomjs_version: 2.1.1 }

License
-------

BSD

Author Information
------------------

UC San Diego Library Development and Operations teams.
