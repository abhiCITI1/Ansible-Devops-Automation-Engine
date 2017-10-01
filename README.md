Ansible and What it does - 

• What is Ansible ?
    Ansible is a configuration management and provisioning tool. With ansible we can automate our deployment process on web/app servers with the help of simple command line scripts. Setting up a server, starting, stopping, restarting and even running the server on a EC2 instance all these can be automated with the help of ansible playbook yml files.

In this tutorial we will go through the process of deploying a simple web page on a web server and the add the web server on an EC2 instance and then accessing the page through browser. All this through ansible. We would set up two web servers: one for testing and one for development, on AWS. We'll install Nginx and configure the environments. Then, lastly, we'll deploy an app.

SSH communications is the key for deploying via Ansible. So, the first part is to setup SSH between our laptop and AWS. Then, we setup local machine for Ansible: install Ansible, writing inventory and playbook. Then, finally, we'll deploy our app by running "ansible-playbook" command.

• Configure Ansible to deploy webserver, and bring it up a port port 80 with a web page that is publically accessible that displays the message: “Hello World”

• Include in the Ansible playbook, plays to deploy and un-deploy the resources (web server) from EC2.
