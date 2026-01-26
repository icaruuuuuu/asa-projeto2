# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "debian/bookworm64"
  config.vm.hostname = "icaro.bruno"
  
  if Vagrant.has_plugin? "vagrant-vbguest"
    config.vbguest.no_install  = true
  end

  config.vm.network "private_network", ip: "192.168.56.108"
  config.vm.network "public_network"

  config.vm.provider "virtualbox" do |vb|
    vb.gui = false
    vb.memory = "1024"
  end
end
