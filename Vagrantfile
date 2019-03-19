Vagrant.configure("2") do |config|
  config.vm.box = "sbeliakou/centos"
  config.vm.define "master" do |master|
    master.vm.network :private_network, ip: "192.168.56.15"
    master.vm.hostname = "master"
  end
  config.vm.define "worker" do |worker|
    worker.vm.network :private_network, ip: "192.168.56.16"
    worker.vm.hostname = "worker"
  end
end