### Lab #7 Adding .kitchen.yml MySQL Cookbook.
1. Edit .kitchen.yml file ( was created with chef generate command)
2. Specify same platform as set in Vagrantfile
3. Set driver
4. Lock omnibus installer version to `12.19.36`
5. Keep verifier inspec
6. Add testing suite with name `default`
7. Set same run_list as set in Vagrantfile

### Tips
Use https://github.com/olebel/gl_mysql as reference Lab #5 solution
Use https://docs.chef.io/config_yml_kitchen.html reference

### Checklist
Make sure you’re able to: `kitchen converge`, `kitchen login`, `kitchen verify`, `kitchen test`
Make sure your code works same way as on vanilla vagrant.
