# EVTchallenge

OS: Ubuntu

Webserver: Nginx

Config management: Code/Shell script

chmod 700 deploy.sh and run the script in a root shell.
After running the script, access localhost or 127.0.0.1. You will see the static web html provided being served.

Synopsis:
I used Nginx to serve the static files, because I have used it before (a reverse proxy server for unblocking my Chinese friends from the CCP Greatwall). Also, it's simple to setup if I just need to serving static files. In this homework, I serve the page by overwriting the index/entry html, so visitor don't have to enter the file name in the route to access that perticular static file. I didn't do any modification on server blocks location/routes, the default server config has all I need.

I don't see a reason to use Ansible or Puppet to automate the deployment on a single server node, so I just going to use script to config/deploy the server.
