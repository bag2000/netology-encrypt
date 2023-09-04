# Домашнее задание к занятию "Защита хоста" - Поляков Р.В.

Любые вопросы по решению задач задавайте в чате учебной группы.

# Задание 1.
Установите eCryptfs.

Добавьте пользователя cryptouser.

Зашифруйте домашний каталог пользователя с помощью eCryptfs.

В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.

___
**Ответ:**

Вначале покажу домашний католог . Добавим пользователя cryptouser.

**Скриншот**

![Домашний католог](https://github.com/bag2000/netology-encrypt/blob/main/1.png)


Зашифруем домашний каталог /home пользователя cryptouser с помощью eCryptfs.

**Скриншот**

![шифрование](https://github.com/bag2000/netology-encrypt/blob/main/2.png)


**Зашифрованный раздел /home**

**Скриншот**

![Видим зашифрованный раздел](https://github.com/bag2000/netology-encrypt/blob/main/3.png)

Возвращяем доступ к файлам папки /home 

**Скриншот**

![Размонтирование и доступ к файлам](https://github.com/bag2000/netology-encrypt/blob/main/4.png)


Как видим доступ появился в домашней папке /home 

# Задание 2.
Установите поддержку LUKS.

Создайте небольшой раздел (например, 100 Мб).

Зашифруйте созданный раздел с помощью LUKS.

В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.

___
**Ответ:**

Зашифруем созданный раздел sbd = 100 Мб с помощью LUKS.

**Скриншот**

![Снимок экрана от 2022-12-04 14-13-37](https://github.com/bag2000/netology-encrypt/blob/main/5.png)

проверяем 

**Скриншот**

![Снимок экрана от 2022-12-04 14-16-32](https://github.com/bag2000/netology-encrypt/blob/main/6.png)


Чтобы расшифровать диск, который был зашифрован с помощью LUKS. Требуется выполнить и смонтировать диск 

**Скриншот**

![Снимок экрана от 2022-12-04 14-18-19](https://github.com/bag2000/netology-encrypt/blob/main/7.png)

точка монтирования для подключенного диска.  /media/mydrive 

проверим

**Скриншот**

![Снимок экрана от 2022-12-04 14-21-35](https://github.com/bag2000/netology-encrypt/blob/main/8.png)

После подключения мы сможем получить доступ к подключенному диску из графического файлового менеджера или из командной строки.
