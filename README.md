# ansible-ec2-provision

**Provisions EC2 Instance by using role and variables file**

### Getting Started:

1. Follow the format of ec2_vars/example_app.yml and provide real values to the variables
2. Pass variable file name as "type=<var_file>" when calling ansible-playbook

#### Example:

*This will take variables from ec2_vars/example_app.yml and pass them into provision-ec2 role*

`shell#: ansible-playbook -vv -i localhost, -e "type=example_app" provision-ec2.yml`
