# upgrade_mariadb

ansible-pull -i hosts -U https://github.com/netispl/upgrade_mariadb
ansible-pull -i hosts -U https://github.com/netispl/upgrade_mariadb -e NRSKL=00 -e BACKUP=no
ansible-pull -i hosts -U https://github.com/netispl/upgrade_mariadb -e NRSKL=00 -e BACKUP=no -e QT=yes
