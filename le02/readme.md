### vagrant
1. vagrant init centos/7
2. vagrant up --> you should install virtualbox to work
3. vagrant ssh-config
4. vagrant ssh 
5. vagrant halt to stop vm 
6. vagrant destroy to delet VM


## vagrantfile

add the following to vagrantfile 
config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end
1. vagrant provision



