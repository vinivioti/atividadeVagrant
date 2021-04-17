Vagrant.configure("2") do |config|
  config.vm.box = "bigdeal/mysql57"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.network "forwarded_port", guest: 3306, host: 3306
  config.vm.hostname = "Mysqlserver"

  config.vm.provider :virtualbox do |vb|
      vb.name = "MySql"
      vb.memory= 2048
      vb.cpus = 1
  end

end