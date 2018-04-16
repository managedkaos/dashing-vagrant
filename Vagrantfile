Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-18.04"
  config.vm.network :forwarded_port, guest: 3030, host: 3030
  config.vm.provision "shell", path: "dashing.sh" 
end
