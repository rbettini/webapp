## Pre-reqs to run this project:

1- Direct internet communication. In case of a intermediate proxy, make shure that the configurations are ok!
2- Installed products:

- Virtual Box
https://www.virtualbox.org/

- Vagrant
https://www.vagrantup.com/downloads.html


#############################################################

## Starting the infrastructure provisioning

- Download "Vagrantfile" file on your computer (https://github.com/rbettini/webapp/blob/master/vagrant/Vagrantfile)
- Create a directory to run vagrant and execute the command bellow in a CMD terminal (or Bash Linux):

  vagrant init

- Replace the Vagrantfile by the Vagrantfile that you have been downloaded.
- Execute this another command in a CMD terminal (or Bash Linux):
  
  vagrant up
  
  
Wait the infrastructure to be provisioned and check it through your local web browser in http://localhost:8080 (should appear "Test OK!")


This automation will provision:

- One Linux CentOS7 VM Instance with 4Gb of memory
- Docker installed and running
- One Apache HTTP Server Instance running in Docker Container

Done!
