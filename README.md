New Installer for V4/PHP7/Debian 8 (Jessie)


So I have updated the old script that I made/modded to now install the following

    PHP7 with needed mods
    MariaDB
    U232 V4
    Webserver - Selectable between nginx and apache2
    phpmyadmin
    HTTPS support with a self-signed certificate (optional)
    XBT (optional)


I'm probably forgetting something

It installs from a blank slate and does not remove anything.

Easiest way to use as root:
wget https://gitlab.open-scene.net/whocares/u232-v4-xbt-mariadb-php5/raw/master/php7.sh
bash php7.sh


OR

probably should just to be safe make that
apt-get update
apt-get install ca-certificates wget
wget https://gitlab.open-scene.net/whocares/u232-v4-xbt-mariadb-php5/raw/master/php7.sh
bash php7.sh




Other install command
chmod +x install.sh
./install.sh

If that doesnt work then try
bash install.sh

