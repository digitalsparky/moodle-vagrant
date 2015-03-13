# moodle-vagrant
Moodle Vagrant installer (Ubuntu 14.04, Apache, PHP5, PostgreSQL, Latest Moodle)

Usage instructions:

- Install Vagrant from https://www.vagrantup.com/downloads.html
- Clone moodle-vagrant:

git clone https://github.com/digitalsparky/moodle-vagrant.git

- Change to moodle-vagrant directory
- Execute vagrant:

vagrant up

Moodle will be available at http://moodle.local/

You will need to add a hosts file entry for:
moodle.local points to 192.168.33.10

Authentication Details:

username: admin
password: Admin1!

This has been tested using Vagrant 1.7.2

