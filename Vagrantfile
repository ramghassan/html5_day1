# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  config.vm.box = "stackroute/html"
  config.vm.box_url = "http://172.23.238.253/vagrant/boxes/stackroute-html.box"

  # Map the guest os port 8080 to host os port 8080
  config.vm.network "forwarded_port", guest: 8088, host: 8088
    config.vm.network "forwarded_port", guest: 9090, host: 9090
      config.vm.network "forwarded_port", guest: 7070, host: 7070

end
