---
title: "KTorrent"
weight: 8
---

Откройте окно «Модули» и установите флажок «Веб-интерфейс».

![plugins](https://user-images.githubusercontent.com/1829509/82014098-4e873a00-9695-11ea-8e8f-dacfbb7bc5ec.png)

Далее откройте окно «Настройки → Настроить KTorrent (Ctrl+P)» и перейдите на вкладку «Веб-интерфейс».
Установите флажок «Требовать ввод пароля». Задайте данные учётной записи (имя пользователя и пароль) для доступа к веб-интерфейсу торрент-клиента. Укажите желаемый порт веб-интерфейса, например, 8081.

Проверьте доступность веб интерфейса по адресу http://127.0.0.1:8081

Продублируйте эти параметры в [настройках](https://github.com/berkut-174/webtlo/wiki/Torrent-clients) торрент-клиентов.

> **ВНИМАНИЕ!** Постарайтесь исключить из логина и пароля специальные символы во избежании проблем с подключением.

![web_interface](https://user-images.githubusercontent.com/1829509/82014094-4deea380-9695-11ea-8be1-ae507e24e927.png)