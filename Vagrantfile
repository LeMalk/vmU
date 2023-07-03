Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"   # Box do Ubuntu 20.04
  config.vm.network "public_network", bridge: "Intel(R) Wireless-AC 9560"   # Modo bridge

  config.vm.synced_folder "/Users/leand/Documents/Vagrant/vmU/", "/vagrant" # Sincronização de pasta

  config.vm.provider "virtualbox" do |vb|
    vb.name = "vm_ubuntu"   # Nome da máquina virtual
    vb.memory = "1024"   # 1GB de memória RAM
    vb.cpus = 1   # 1 CPU
  end
end
