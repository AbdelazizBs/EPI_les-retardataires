Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.network "public_network" , ip: "20.50.0.145"

  config.vm.provider "virtualbox" do |vb|
    vb.cpus = 2
    vb.memory = "4096"
  end

  
#  config.vm.provision "shell" do |shell|
#   shell.path = "jenkins.sh"
#  end

end