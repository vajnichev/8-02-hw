# Домашнее задание к занятию "`Что такое DevOps. CI/CD`" - `Важничев Георгий`


### Задание 1

`**Что нужно сделать:**`

1. `Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.`
2. `Установите на машину с jenkins golang.`
3. `Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.`
4. `Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..`

`В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.`


1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.

![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.1.1.png)

2. `Установите на машину с jenkins golang.`

![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.1.2.png)

3. `Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.`

![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.1.3.png)

4. `Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..`

![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.1.4.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.1.8.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.1.5.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.1.6.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.1.7.png)



### Задание 2

`Что нужно сделать:`

1. `Создайте новый проект pipeline.`
2. `Перепишите сборку из задания 1 на declarative в виде кода.`

`В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.`

![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.2.1.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.2.2.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.2.3.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.2.4.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.2.5.png)


### Задание 3

`Что нужно сделать:`

1. `Установите на машину Nexus.`
2. `Создайте raw-hosted репозиторий.`
3. `Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.`
4. `Загрузите файл в репозиторий с помощью jenkins.`

`В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.`

![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.3.1.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.3.2.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.3.3.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.3.4.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.3.5.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.3.6.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.3.7.png)
![img](https://github.com/vajnichev/8-02-hw/blob/main/screen/8.3.8.png)


