# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "shadowrobot/ros-indigo-desktop-xfce-trusty64.box"

  config.vm.provision "shell", inline: <<-SHELL
     sudo apt-get update
  SHELL
end
