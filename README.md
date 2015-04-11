ryane-dotfiles
=========

This is a role I use to setup my personal dotfiles on servers I control. Feel free to use but it is really specific for me.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

* ryane_dotfiles_user_name

defaults to "ryan".

* ryane_dotfiles_dotfiles_directory

The directory (relative to the user home directory) where the ryane/dotfiles repository is checked out to.

defaults to ".dotfiles"

* RYANE_DOTFILES_PASSWORD

This must be set before running the playbook

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ryane.ryane-dotfiles, ryane_dotfiles_user_name: ryan }

License
-------

BSD

Author Information
------------------

Ryan Eschinger
http://ryaneschinger.com
