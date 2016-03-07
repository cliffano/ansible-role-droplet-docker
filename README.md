Droplet Docker
--------------

Ansible role for setting up Docker on DigitalOcean droplet as per [guide](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-getting-started)

Usage
-----

Add the role to playbook:

    - hosts: all
      roles:
        - { role: cliffano.droplet-docker }
