Vagrant.configure("2") do |config|

  config.vm.define "web" do |web|
    web.vm.box = "hashicorp/precise64"
    web.vm.network "private_network", ip: "192.168.50.4"
  end
  config.vm.define "db" do |db|
    db.vm.box = "hashicorp/precise64"
    db.vm.network "private_network", ip: "192.168.50.3"
  end
end
