# Deploy-PHP-app-using-Jenkins-to-AWS-EC2
Install dependencies on server

sudo apt install php
sudo apt update && sudo apt upgrade
sudo apt install software-properties-common
sudo add-apt-repository ppa:ondrej/php
php -v

curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer

#If this Error:  /var/lib/jenkins/workspace/Php/Deploy-PHP-app-using-Jenkins-to-AWS-EC2/vend  
  or does not exist and could not be created.    
#Apply below cmd
sudo chmod -R 777 /var/lib/jenkins/workspace