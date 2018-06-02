# cloud-init

Collection of cloud-init configuration for various tasks.

## engineer-control-center

Cloud-init configuration that sets up the following software on a cloud server.

1. Python PIP
2. Terraform 
3. Ansible
4. Git
5. CLI from cloud providers
    * OpenStackClient - OpenStackClient provides CLI based access to manage the OpenStack infrastructure.
    * Azure CLI v2.0 - Used to manage resources on Azure.
    * Google Cloud SDK - Google Cloud SDK to manage resources on Google Cloud Platform.
    * Amazon Web Service CLI - Used to manage resources on Amazon Web Services.
    * doctl - Used to manage resources on Digital Ocean.

Details at http://www.opentechshed.com/modern-day-engineers-control-center

## lemp-ubuntu-16.04

Cloud-init configuration that sets up the LEMP stack on 

1. DigitalOcean Ubuntu 16.04 Droplet
2. AWS Ubuntu 16.04 AMI

Details at https://www.opentechshed.com/lemp-stack-using-cloud-init
