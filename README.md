Role Name
=========

The role objective is to automate the process of installing the unifi controller on a raspberry pi.

Requirements
------------

In order to use this role you need to install the community.general.modprobe plugin
You need root privileges to run this script.

    become: yes


Example Playbook
----------------

Installing the play

    ansible-galaxy install git+https://github.com/Mot93/rpi-install-unifi-controller.git

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: raspberry
      remote_user: pi
      become: yes
      roles:
        - rpi-install-unifi-controller

License
-------

MIT

Author Information
------------------

If you like my work and want to know more, visit my website:
[mattiarubini.com](https://www.mattiarubini.com)
