# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "meansible"
  config.vm.network :private_network, ip: "172.111.111.111"
  config.vm.provider :virtualbox do |v|
    v.name = "meansible"
    v.memory = "1024"
  end
  config.vm.provision :ansible do |ansible|
    ansible.playbook = "provisioning/playbook.yml"
  end
end
