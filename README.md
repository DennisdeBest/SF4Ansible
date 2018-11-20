# Ansible roles for SF4 development

## Usage

- Put you symfony root files inside the project folder
- Copy Vagrantfile.dist to Vagrantfile and replace MyProjectName with the name of your project, you can also adjust the ip address and other settings like the number of vCPUs or ram used by the virtual machine
- Set the project name inside provision/group_vars/vars.yml
- Adjust any settings/roles inside provision/playbook.yml
- Check that the ip address inside provision/hosts matches the ip address inside the Vagrantfile

run 

```
vagrant up 
``` 
to create the virtual machine
