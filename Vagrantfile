Vagrant.configure('2') do |config|
  config.vm.box = 'terrywang/archlinux'

  config.vm.network :forwarded_port, guest: 5000, host: 5000
  config.vm.network :forwarded_port, guest: 5001, host: 5001

  config.vm.provision :ansible_local do |ansible|
    ansible.compatibility_mode = '2.0'
    ansible.playbook = 'playbook.yml'
  end

  config.vm.provider :virtualbox do |v|
    v.cpus = 2
  end
end
