# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "geerlingguy/centos8"
  config.ssh.insert_key= false
  config.vm.synced_folder ".", "/vagrant", disabled: true

  config.vm.provider:virtualbox do |v|
    v.memory = 3000
    v.linked_clone=true
  end

  #App server 1
  config.vm.define "minikube" do |minikube|
    minikube.vm.hostname = "minikube.test"
    minikube.vm.network :private_network, ip: "192.168.60.7"
  end


end

