Vagrant.configure("2") do |config|
   config.ssh.insert_key = false
#   config.ssh.private_key_path =
  config.vm.box = "fewpixels/centos8_base"
  config.vm.box_version = "0.1.0"
#   config.vm.network :private_network, ip: "192.168.33.33"
#   config.vm.forward_port("ssh", 22, 2222)
  config.vm.provider :virtualbox do |virt|
    virt.memory = 512
    virt.cpus = 1
  end

#   config.vm.provision "ansible" do |ansible|
#     ansible.compatibility_mode = "2.0"
#     ansible.verbose = "v"
#     ansible.playbook = "vagrant.yml"
#     ansible.inventory_path = "hosts.yml"
#     ansible.become = true
#   end
end