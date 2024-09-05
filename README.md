# Jenkins-Nginx
This repository has been created to understand concepts of Dockerfile, Docker compose, Docker containers, NGINX Reverse Proxy, Port Mapping.

#Setup
Pre-Requiste:
1) Docker
2) Any IDE like VS Code etc.
3) Linux/MAC preferred OS.
Steps:
1) Clone into Local and check proper paths for your jenkins_home directory
2) docker compose build && docker compose up -d
3) localhost:8080 shoudl show Jenkins loading
4) after everything is up make sure to give host mount point of jenkins_home chmod -R 755 permissions to full folder. (Note: This is a limitation of setup and will be rectified with modifying entrypoint of Docker soon.)
Future Release:
1) Add docker-entrypoint to add custome roles.
2) Add github Oauth in Jenkins
3) Encrypt localhost with SSL using Open SSL concepts.


