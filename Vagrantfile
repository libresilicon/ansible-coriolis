# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "8192"
    vb.cpus = "8"
    vb.customize ["modifyvm", :id, "--hwvirtex", "on"]
  end

  config.vm.box = "ubuntu/trusty64"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "install.yml"
  end

end
