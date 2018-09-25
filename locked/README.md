
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Hi there! Welcome to Cloud9 IDE!

Steps To Install laravel Latest Version 

1) Update PHP to latest version i.e. PHP 7.2

2) sudo add-apt-repository ppa:ondrej/php -y
    
3) sudo apt-get update -y
4) sudo apt-get install php7.2-curl php7.2-cli php7.2-dev php7.2-gd php7.2-intl php7.2-json php7.2-mysql php7.2-opcache php7.2-bcmath php7.2-mbstring php7.2-soap php7.2-xml php7.2-zip -y
5) sudo mv /etc/apache2/envvars /etc/apache2/envvars.bak
6) sudo apt-get remove libapache2-mod-php5 -y
   sudo apt-get remove libapache2-mod-php7.2 -y    
7) sudo cp /etc/apache2/envvars.bak /etc/apache2/envvars
8) sudo a2dismod php5
9) sudo a2enmod php7.2
10) sudo nano /etc/apache2/sites-enabled/001-cloud9.conf
11) sudo service apache2 restar
12) Get Laravel Installer using following url
    sudo composer global require 'laravel/installer'