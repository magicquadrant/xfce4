# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty32"
  config.vm.provision "shell", path: "xfce_config.sh"
  config.vm.provider "virtualbox" do |v|
	v.gui = true
  end
end
