# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
 
  # config.vm.box = "bento/centos-7"
  config.vm.box = "centos/7"
  config.vm.network "private_network", ip: "192.168.50.10"

  config.vm.synced_folder ".",
    "/vagrant",
    owner: "root",
    group: "root",
    mount_options: [
      # Avoid some program errored due to excessive access from `other`
      "fmode=0770",
      "dmode=0770"
    ]


end
