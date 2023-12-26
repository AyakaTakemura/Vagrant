Vagrant.configure("2") do |config|
   config.vm.box = "centos/7"
   config.vm.network "private_network", ip: "192.168.56.15" #追加 
   config.vm.synced_folder "./", "/var/www/html/", owner: 'menta', group: 'menta'
   config.vm.boot_timeout = 600
end
