# Monter un serveur LAMP grâce à Docker
Exemple de docker-compose pour créer un server LAMP :
 - Linux
 - Apache
 - MySQL
 - PHP
 - PHPMyAdmin

 ## Installation de Docker (Debian / Ubuntu)
 sudo apt update
 sudo apt install docker.io
 sudo usermod -aG docker $USER
 sudo apt install docker-compose

 ## Lancer le docker compose
 docker-compose up -d

 ## Ports
 Serveur Web : 80
 MySQL : 3306
 PHPMyAdmin : 8080
