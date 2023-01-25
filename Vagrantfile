Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.provider "virtualbox" do |vb|
  vb.name = "desafio-02"
      end

  

   config.vm.provision "shell", inline: <<-SHELL
   apt-get update
   apt-get install -y vim curl telnet unzip wget net-tools htop nmap 
   SHELL
end
