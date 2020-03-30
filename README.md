# moodle-vagrant
Moodle Vagrant installer (Ubuntu 18.04, Apache, PHP7, PostgreSQL, Latest Moodle)

This is perfect for local testing and development installations.

Requirements:

- Vagrant ( https://www.vagrantup.com/downloads.html )
- vagrant-vbguest ( https://github.com/dotless-de/vagrant-vbguest )
- VirtualBox ( https://www.virtualbox.org/ )

Usage instructions:

- Clone moodle-vagrant:

git clone https://github.com/digitalsparky/moodle-vagrant.git

- Change to moodle-vagrant directory
- Execute vagrant:

vagrant up

Moodle will be available at http://moodle.local/

You will need to add a hosts file entry for:
moodle.local points to 192.168.33.10

Authentication Details:

- username: admin
- password: Admin1!

This has been tested using Vagrant 1.8.5

# Like my stuff?

Would you like to buy me a coffee or send me a tip?
While it's not expected, I would really appreciate it.

[![Paypal](https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png)](https://paypal.me/MattSpurrier) <a href="https://www.buymeacoffee.com/digitalsparky" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/white_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
