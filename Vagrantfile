Vagrant.configure("2") do |config|

  config.vm.define "scriptbox" do |scriptbox|
    scriptbox.vm.box = "geerlingguy/centos7"
	scriptbox.vm.network "private_network", ip: "192.168.52.12"
	scriptbox.vm.provider "virtualbox" do |vb|
     vb.memory = "1024"
   end
  end

  config.vm.define "myweb" do |myweb|
    myweb.vm.box = "geerlingguy/centos7"
	myweb.vm.network "private_network", ip: "192.168.52.13"
  end
  
  config.vm.define "myweb2" do |myweb2|
    myweb2.vm.box = "geerlingguy/centos7"
	myweb2.vm.network "private_network", ip: "192.168.52.14"
  end

   config.vm.define "myweb3" do |myweb3|
    myweb3.vm.box = "ubuntu/bionic64"
        myweb3.vm.network "private_network", ip: "192.168.52.15"
  end
end
