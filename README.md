# moodle-vagrant
Moodle Vagrant installer (Ubuntu 14.04, Apache, PHP5, PostgreSQL, Latest Moodle)

This is perfect for local testing and development installations.

Requirements:

- Vagrant ( https://www.vagrantup.com/downloads.html )
- VirtualBox ( https://www.virtualbox.org/ )
- git

Usage instructions:

- Clone moodle-vagrant and switch to stack branch:
  - git clone https://github.com/whanrott/moodle-vagrant.git
  - git branch moodle_stack origin/moodle_stack
  - git checkout moodle_stack

- Change to moodle-vagrant directory
- Execute vagrant:
  - vagrant up

Find the /hosts/ file and add this line:
192.168.33.10	moodle.local

This will enable Moodle at http://moodle.local/

Authentication Details:

- username: admin
- password: Admin1!

This has been tested using Vagrant 1.7.4

The build of STACK will run more slowly because it has not been optimised. 
The script to run the optimisation is in the file optimise_stack.txt. You
will need to have connected to the vagrant box using the command vagrant ssh.
Then go to the STACK plugin config in Moodle and follow the instructions here:
http://moodle.local/question/type/stack/doc/doc.php/CAS/Optimising_Maxima.md

Optimising STACK in Moodle is optional for performance. You will need to run 
the optimising script every time you update the STACK plug-in.
