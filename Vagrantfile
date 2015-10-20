VAGRANTFILE_API_VERSION = "2"

# Debian box

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  # Use the same key for each machine
  config.ssh.insert_key = false

  config.vm.define "test" do |vagrant1|
    vagrant1.vm.hostname = "test-server"
    vagrant1.vm.box = "debian/jessie64"
    vagrant1.vm.network "private_network", ip: "192.168.35.10"
  end
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "1024"
  end
end
