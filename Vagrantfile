# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.network "forwarded_port", guest: 8000, host: 8000
  # config.vm.network "forwarded_port", guest: 5432, host: 5432
  config.vm.provision "shell", path: "https://raw.githubusercontent.com/mostlyclicks/vagrant_provision/master/provision.sh"
  # config.vm.provision "shell", path: "provision.sh"
end