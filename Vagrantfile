Vagrant.configure("2") do |config|
    config.vm.provision :shell, path: "provision.sh"
    
    config.vm.define "dev-server" do |dev|
      dev.vm.hostname = "dev-server"
      dev.vm.box = "hashicorp/bionic64"
      dev.vm.synced_folder "src", "/home/vagrant/src"
    end
end