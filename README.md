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
![image](https://am3pap003files.storage.live.com/y4mLbRF2zsFhc1BU4bF7RTUQJ4u5JbH6s5ZkoFpvBO3tDbK1AXnOkZA2kShWw18P5n8uhyNWPIxIFrYlwyguBZhbgks_meCzQ3laUjBuiFzXNSlhZNUt9VWgJwKedik7xhEPi3l3x_3v1qxFp-szOQq9kDC2GUQdczyBzBLC5vL4Qs7Wh9obto_kzqM8E_gYg2a?encodeFailures=1&width=683&height=101)

## VM2 postgresql-13
![image](https://am3pap003files.storage.live.com/y4mldRd6z-_3rVtwfW1Qjn-mp3xL7KE2s4_NqEV31ne_EoTkI_FJwHuLiSm3p6cWUXPnOHbOj3sy4W7yP9qoWStIaZHQBppdAt4tXIntwrxrTUWg6Zg3V5NHy0tPLImOVRy6GSegWE3S3YK9SsUu8YaEsu_5cwR1BssNTLlacdvbAM6pqylOxXjfmKY-a99jrzO?encodeFailures=1&width=767&height=105)


## Django Admin command
![image](https://am3pap003files.storage.live.com/y4mWCkMbo__8CoOWRCD9eFWKaF5ovtsbgJMMfTMOAIuoIlZgaRRp_0VsViuYxi0PZDF98NDaqm4rhYfZz6qV2hdR5eqDR_BMLzqPAdPBr9D0qtb2_U72pQAX_XddAH_GNCA4yjSRxAi_fZSHnSLT3cRfGCNsZoN9i2deH71jJVwDa2ZoERZPbMcjwDbowv69pOP?encodeFailures=1&width=672&height=58)