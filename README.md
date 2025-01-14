# Wordpress-Project-Starter
TODO: Setup Vagrant provisioning for Apache and MySQL

Local Machine Dependencies: VirtualBox & Vagrant for running virtual environment.

Goal: One click wordpress project startup for having wordpress, apache routing, and database ready to go



For now:

Add MySQL user with the following:

sudo mysql -u root -p
Password: root

CREATE USER 'vagrant'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON *.* TO 'vagrant'@'localhost' WITH GRANT OPTION;


Update Apache config at /etc/apache2/sites-enabled to route to public_html
