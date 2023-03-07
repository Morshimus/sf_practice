# SkillFactory B-10 Project

## Задание

* [x] - :one: **Создать на GitHub профиль и репозиторий под названием sf_practice, в нем создать директорию с названием «6».**
* [x] - :two: **На своей локальной машине (ПК/ноутбук/etc) настроить связку Vagrant+VirtualBox.**
* [x] - :three: **Создать пустой файл на файловой системе этой хостовой машины.**
> Какая то глупость, я создал файл django.conf с настройкой имени db.
* [x] - :four: **Создать Vagrantfile, при использовании которого будет создаваться ВМ под управлением Ubuntu 18.04.**
> Готово
* [x] - :five: **Настроить Vagrantfile таким образом, чтобы на эту машину при ее создании установились python3- и python3-pip-пакеты, а также Python-библиотеки psycopg2 (для подключения к PostgreSQL СУБД) и Django (для работы с фронтендом).**
> Был использован файл requirements.txt для ведения версионности библиотек psycopg2 и Django.
* [x] - :six: **Дополнить Vagrantfile командой копирования созданного нами пустого файла на файловую систему созданной машины (в будущем при реальной работе с тестовым окружением, разработчики будут вместо этого пустого файла копировать на создаваемую ВМ свои скрипты и запускать их там).**
> Скопировал файлы на Виртуалки
* [x] - :seven: **Отправьте этот Vagrantfile в созданный в п.1 репозиторий в директорию «6».**
* [x] - :eight: **Отправьте ментору ссылку на Vagrantfile в вашем репозитории.**
> Сделал 2 виртуалки с разныеми дистрами Postgresql 12 - 13 - все остальное одинаковое. Для дальнейших эксперементов можно менять файлы requirements.txt (тест совместимости версий библиотек python3) и следовательно менять характеристики в Vagrantfile производительности.
![image](https://am3pap003files.storage.live.com/y4mF19IfMTPFSUfFZa0LRX_KYCHEWKAEsjMI1Rz1HLfQl0HpBv2B0teZ6iq40Yi9sH2_LYcnaJieWK3E2_fuFY1clruZeZo1XVhc5jbTL0jNlkj0DAeCxCq9Tix07MQhUopw4s0aFTABY6hQduHQ7ilBp4FTjaelD7bclXmDY3qZNVXf1oqI_HCLhysF1ok9x4K?encodeFailures=1&width=1383&height=685)

## VM1 postgresql-12
![image]()

## VM2 postgresql-13
![image]()


## Django Admin command
![image]()