
Vagrant.configure("2") do |config|
  config.vm.define "centos-admin" do |vm1|
    vm1.vm.hostname = "centos-admin"
    vm1.vm.box = "jasonc/centos7"
    vm1.vm.network "private_network", ip: "192.168.33.10"
  end

  config.vm.define "centos-server" do |vm2|
    vm2.vm.hostname = "centos-server"
    vm2.vm.box = "jasonc/centos7"
    vm2.vm.network "private_network", ip: "192.168.33.20"
  end

end
