## Informacje
Playbook do aktualizacji MariaDB oraz kompilacji Hipermarkru z nowymi bibliotekami.


## Wymagania
Do uruchomienie playbooka wymagane są pakiery git oraz ansible
 ``` 
 sudo apt-add-repository --yes ppa:ansible/ansible
 sudo apt-get update && apt-get install --yes git ansible
```

## Instalacja
Uruchomienie playbooka z róznymi opcjami:
```
sudo ansible-pull -i hosts -U https://github.com/netispl/upgrade_mariadb
sudo ansible-pull -i hosts -U https://github.com/netispl/upgrade_mariadb -e NRSKL=00 -e BACKUP=no
sudo ansible-pull -i hosts -U https://github.com/netispl/upgrade_mariadb -e NRSKL=00 -e BACKUP=no -e QT=yes
```
