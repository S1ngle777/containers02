# IWNO2: Первый контейнер
## Цель работы
Данная лабораторная работа знакомит с основами контейнеризации и подготавливает рабочее место для выполнения следующих лабораторных работ.
## Задание
Установить Docker Desktop и проверить его работоспособность.
## Описание выполнения работы
Откройте терминал в папке containers02 и выполните команду:
```
docker build -t containers02 .
```
Сколько времени создавался образ?

__34 секунды__

![image](https://github.com/S1ngle777/containers02/assets/128795707/3296d7f9-a2c7-4ee5-a793-4e7a115b72d7)

Выполните команду для запуска контейнера:
```
docker run --name containers02 containers02
```
Что было выведено в консоли?

![image](https://github.com/S1ngle777/containers02/assets/128795707/177e2a32-33f2-4194-98de-a8037599b561)

Удалите контейнер и запустите снова, выполнив команды:
```
docker rm containers02
docker run -ti --name containers02 containers02 bash
```
В открывшемся окне выполните команды:
```bash
cd /var/www/html/
ls -l
```
Что было выведено в консоли?

Удалите контейнер и запустите снова, выполнив команды:
```
docker rm containers02
docker run -ti --name containers02 containers02 bash
```
В открывшемся окне выполните команды:
```
cd /var/www/html/
ls -l
```
Что выводится на экране?

Закройте окно командой exit.

## Выводы
## Используемые источники
