# v2board-install-auto

Install automation v2board in your server

This script install bbr, nginx, php8.1, composer, mariadb10.4, nodejs(pm2) and config automation for v2board and install and config ssl for your domain

Also this script create database with v2board name and create user v2board with random password who give you in terminal

Before run script set A record domain to ip for instaling ssl




Easy install:
<pre><code>curl -O https://raw.githubusercontent.com/miladrajabi2002/v2board-install-auto/master/install.sh && chmod +x ./install.sh && ./install.sh</code></pre>
