# Monter un serveur LAMP grâce à Docker
Exemple de docker-compose pour créer un server LAMP :
 - Linux
 - Apache
 - MySQL
 - PHP
 - PHPMyAdmin

 ## Installation de Docker (Debian / Ubuntu)
 sudo apt update<br/>
 sudo apt install docker.io<br/>
 sudo usermod -aG docker $USER<br/>
 sudo apt install docker-compose<br/>

 ## Lancer le docker compose
 docker-compose up -d

 ## Arrêter le docker compose
 docker-compose down

 ## Ports
 Serveur Web : 80<br/>
 MySQL : 3306<br/>
 PHPMyAdmin : 8080<br/>
