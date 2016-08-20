# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  # Every Vagrant development environment requires a box. You can search for
  # boxes at https://atlas.hashicorp.com/search.
  # Please replace it with a BOX name of CentOS6 for one's own 32bit when your host is 32bit machine.
  config.vm.box = "geerlingguy/centos6"

  # Add ansible provisioner
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "site.yml"
  end
end
