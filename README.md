#Installer for V4/PHP7/Debian 8 (Jessie)


Updated everything in the script to:

    PHP7 with needed mods
    MariaDB
    U232 V4
    Webserver - Selectable between nginx and apache2
    phpmyadmin
    HTTPS support with a self-signed certificate (optional)
    XBT (optional)




It installs from a blank slate and does not remove anything.

##Install


`apt-get update && apt-get install ca-certificates wget -y`

---

`wget https://gitlab.open-scene.net/whocares/u232-v4-xbt-mariadb-php5/raw/master/php7.sh`

`bash php7.sh`



###Other install command
`chmod +x install.sh`

then

`./install.sh`

If that doesn't work then try:

`bash install.sh`

