Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-22.04"
  config.vm.hostname = "vault-server"
  config.vm.network "public_network", bridge: 'en0: Wi-Fi (AirPort)'
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"
    vb.cpus   = 2
  end
end
