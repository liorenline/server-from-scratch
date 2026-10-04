# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.box = "utm/ubuntu-24.04"
  config.vm.box_check_update = false
  config.vm.hostname = "srv-dev"
  config.vm.define "srv-dev"

  config.vm.provider :utm do |u|
    u.memory = 2048
    u.cpus = 2
  end
end