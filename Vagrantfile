# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure('2') do |config|
  config.vm.define 'grimmjow8' do |c|
    c.vm.box = 'npalm/mint17-amd64-cinnamon'
    c.vm.network :private_network, ip: '192.168.88.21'
    c.vm.hostname = 'grimmjow8.local'
    c.vm.provision 'ansible' do |ansible|
      ansible.playbook = 'tests/test.yml'
      ansible.sudo = false
 #     ansible.verbose = 'vvv'
      ansible.host_key_checking = false
    end
  end
end
