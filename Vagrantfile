Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |vb|
    vb.name = "ubuntu_vm"
  end
  config.vm.box = "hashicorp/bionic64"
  config.vm.provision "shell", path: "script.sh"
end
