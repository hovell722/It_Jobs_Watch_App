
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/bionic64"
  config.vm.synced_folder "it_jobs_watch_code", "/home/ubuntu/app"
  config.vm.provision "shell", path: "provisions.sh"

end
