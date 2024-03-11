Vagrant.configure("2") do |config|
  # Web01 VM (Ubuntu 22.04)
  config.vm.define "web01" do |web01|
    web01.vm.box = "generic-x64/ubuntu2204"
    web01.vm.network "private_network",ip: "192.168.33.11"
    web01.vm.hostname = "web01"
  end

  # Web02 VM (Ubuntu 22.04)
  config.vm.define "web02" do |web02|
    web02.vm.box = "generic-x64/ubuntu2204"
    web02.vm.network "private_network", ip: "192.168.33.12"
    web02.vm.hostname = "web02"
  end

  # Web03 VM (Ubuntu 22.04)
  config.vm.define "web03" do |web03|
    web03.vm.box = "generic-x64/ubuntu2204"
    web03.vm.network "private_network", ip: "192.168.33.13"
    web03.vm.hostname = "web03"
  end
end
