# Docker-Container-Ansible-Playbook-
## Task Description
- Configure Docker 
- Start and enable Docker services 
- Run the docker container and expose it to the public 
- Retrieve new Container IP and update the inventory 
- Copy the html code in /var/www/html directory and start the web server. Do further Configuration of Webserver inside that Container.

## Note: Run Playbook in following order: 1) docker_cont.yml 2) doct_cont2.yml
## *Important Note*: doct_cont2.yml will run successfully only when we are running this playbook on ansible host as it uses ssh to configure and docker container IP are local so they can easily use ssh to configure. *It won't configure on remote docker container*

# Article: https://yuktachakravarty.medium.com/ansible-playbook-that-retrieves-new-container-ip-update-inventory-and-configure-webserver-using-c662e93f4fa4
