ENV['VAGRANT_DEFAULT_PROVIDER'] = 'docker'
 
Vagrant.configure("2") do |config|

  config.vm.define "lo_platform_linux32" do |a|
    a.vm.provider "docker" do |d|
      d.build_dir = "lo"
      d.build_args = ["-t=lo_platform_linux32"]
      d.name = "lo_platform_linux32"
      d.remains_running = false
      d.vagrant_machine = "dockerhost-linux32"
      d.vagrant_vagrantfile = "./DockerHostVagrantfile"
    end
  end

  config.vm.define "hb_platform_linux32" do |a|
    a.vm.provider "docker" do |d|
      d.build_dir = "hb"
      d.build_args = ["-t=hb_platform_linux32"]
      d.name = "hb_platform_linux32"
      d.remains_running = false
#      d.vagrant_machine = "dockerhost-linux32"
#      d.vagrant_vagrantfile = "./DockerHostVagrantfile"
    end
  end

  config.vm.define "psql_platform_linux32" do |a|
    a.vm.provider "docker" do |d|
      d.build_dir = "postgresql"
      d.build_args = ["-t=psql_platform_linux32"]
      d.name = "psql_platform_linux32"
      d.remains_running = false
      d.vagrant_machine = "dockerhost-linux32"
      d.vagrant_vagrantfile = "./DockerHostVagrantfile"
    end
  end


  config.vm.define "jvm_platform_linux32" do |a|
    a.vm.provider "docker" do |d|
      d.build_dir = "jvm"
      d.build_args = ["-t=jvm_platform_linux32"]
      d.name = "jvm_platform_linux32"
      d.remains_running = false
      d.vagrant_machine = "dockerhost-linux32"
      d.vagrant_vagrantfile = "./DockerHostVagrantfile"
    end
  end

  config.vm.define "f18_linux32" do |a|
    a.vm.provider "docker" do |d|
      d.build_dir = "f18"
      d.build_args = ["-t=f18_linux32"]
      d.name = "f18_linux32"
      d.remains_running = false
      d.vagrant_machine = "dockerhost-linux32"
      d.vagrant_vagrantfile = "./DockerHostVagrantfile"
    end
  end


end
