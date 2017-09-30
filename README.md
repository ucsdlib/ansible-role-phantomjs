PhantomJS
=========

[![Build Status](https://travis-ci.org/ucsdlib/ansible-role-phantomjs.svg?branch=master)](https://travis-ci.org/ucsdlib/ansible-role-phantomjs)

Installs [PhantomJS](http://phantomjs.org/) via provided tar for linux x86/64.

Requirements
------------

No external requirements.

Role Variables
--------------

* `phantomjs_version`: Desired version to install (2.1.1)
* `phantomjs_checksum`: Checksum from provided download page
* `phantomjs_checksum_algorithm`: Checksum algorithm to use (sha256, md5)
* `phantomjs_install_dir`: Location to install (/opt)
* `phantomjs_download_dir`: Location to install (/tmp)
* `phantomjs_bin_dir`: Location to install symlink (/usr/local/bin)

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

BSD 2

Author Information
------------------

UC San Diego Library Development and Operations teams.
