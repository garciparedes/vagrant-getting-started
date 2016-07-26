# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

    config.vm.box = "hashicorp/precise64"

    config.vm.box_version = "1.1.0"
    config.vm.box_url = "http://files.vagrantup.com/precise64.box"

    config.vm.provision :shell, path: "bootstrap.sh"

    config.vm.network :forwarded_port, guest: 80, host: 4567

end
