Vagrant.configure("2") do |config|
    config.vm.box = "ubuntu/bionic64"
  
    config.vm.define "server1" do |server|
      server.vm.network "private_network", ip: "192.168.56.2"
      server.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  
    config.vm.define "server2" do |server|
      server.vm.network "private_network", ip: "192.168.56.3"
      server.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  
    config.vm.define "server3" do |server|
      server.vm.network "private_network", ip: "192.168.56.4"
      server.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  end
  