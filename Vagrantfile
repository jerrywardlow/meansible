# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "meansible"
  config.vm.network :private_network, ip: "192.168.56.2"
  config.vm.provider :virtualbox do |v|
    v.name = "meansible"
    v.memory = "512"
  end
end
