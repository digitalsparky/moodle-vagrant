# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure(2) do |config|
	config.vm.hostname = 'moodle.local'
	config.vm.box = "ubuntu/trusty64"
	config.vm.network "private_network", ip: "192.168.33.10"
	config.vm.synced_folder "./moodle/", "/var/www/moodle", create: true, owner: 'www-data', group: 'www-data'
	config.vm.provider "virtualbox" do |vb|
		vb.name = "moodle"
		vb.memory = 1024
		vb.cpus = 2
	end
	config.vm.provision "shell", inline: <<-SHELL
		sudo bash /vagrant/provision.sh
	SHELL
end