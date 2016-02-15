Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.provision "install_dependencies", type: "shell", path: "bin/install_dependencies.sh"
  config.vm.provision "build", type: "shell", path: "bin/build.sh"
end
