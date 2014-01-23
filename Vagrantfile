# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
	config.vm.box = "boot2docker"
	config.vm.box_url = "https://github.com/brimstone/boot2docker-vagrant-box/releases/download/v0.3.0-1%2Bvbox4.2/boot2docker.box"

	config.vm.network :forwarded_port, guest: 8080, host: 8080

	#config.vm.provision "shell", inline: $script
end
