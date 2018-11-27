# EVTchallenge

OS: Ubuntu

Webserver: Nginx

Config management: Code/Shell script

chmod 700 deploy.sh and run the script in a root shell.
After running the script, access localhost or 127.0.0.1. You will see the static web html provided being served.

I don't see a reason to use Ansible or Puppet to automate the deployment on a single server node, so I just going to use script to config/deploy the server.
