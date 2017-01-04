Docker-Gen
==========

Docker-gen listens to Docker events and creates files from templates. This role is specific to create local nginx vhost configurations for docker containers.

More info on docker-gen can be found here: https://github.com/jwilder/docker-gen

Requirements
------------

On your machine you should have Nginx and Docker running.

Role Variables
--------------

There are no variables yet.

Dependencies
------------

There are no ansible dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: neckhair.docker-gen }

License
-------

BSD
