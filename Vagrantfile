Vagrant::Config.run do |config|
  # All Vagrant configuration is done here. For a detailed explanation
  # and listing of configuration options, please view the documentation
  # online.
  # Every Vagrant virtual environment requires a box to build off of.
  config.vm.box = "lucid32"

  config.vm.provisioner = :chef_solo
  config.chef.cookbooks_path = "cookbooks"

  # Tell chef what recipe to run. In this case, the `vagrant_main` recipe
  # does all the magic.
  config.chef.add_recipe("vagrant_main")
end