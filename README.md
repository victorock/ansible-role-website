Role Name
=========

Role to deploy Website

Requirements
------------

Webserver with PHP and Mysql connectivity.

Role Variables
--------------

website_name: website
website_version: 0.1
website_path: "/var/www/html"
website_user_owner: "httpd"
website_user_group: "httpd"
website_database_pool: "db"


Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: website
      roles:
        - role: victorock.website
          website_name: MyWebsite
          website_version: 0.1
          website_path: "/var/www/html"
          website_user_owner: "httpd"
          website_user_group: "httpd"
          website_database_pool: "db"

License
-------

BSD

Author Information
------------------

https://github.com/victorock
