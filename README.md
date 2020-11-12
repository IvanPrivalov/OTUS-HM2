# OTUS-HM2
Домашнее задание. Работа с mdadm.

# Инструкция
Копируем Vagrantfile в каталог
Открываетм консоль
Переходим в каталог где лежит Vagrantfile
Выполняем команду vagrant up
После выполнения вводим команду vagrant ssh
Для проверки запускаем команду lsblk, cat /proc/mdstat, mdadm -D /dev/md0
Проверем mdadm.conf выполнив команду vi /etc/mdadm/mdadm.conf

