Vagrant.configure(2) do |config|
  # create the master node
  config.vm.define "master" do |master|
    master.vm.box = "ubuntu/focal64"
    master.vm.hostname = "Master"
    master.vm.network "private_network", ip: "192.168.33.10"
    master.vm.boot_timeout = 1200
   #master.vm.provision "shell", path: "lamp.sh"
   #master.vm.provision "shell", path: "laravel.sh"
  end

end


