# Lib-doc

## Описание проекта
Alefowl - это open source проект посвящен билингвальному чтению 

## Предусловие
+ скачать и установить базу данных (PostgreSQL)
https://www.postgresql.org/
+ скачать и установить Git
https://git-scm.com/
+ скачать и установить Node.js
https://nodejs.org/ru
+ скачать и установить Java
"https://www.java.com/ru/download/manual.jsp

## Инструкция

Установка бэкенд (Java JAR):
Скачать и установить Java на компьютер "https://www.java.com/ru/download/manual.jsp
```
Запросить у наставника jar файл бекенда
```
Открыть jar файл с помощью Winrar или Zip
```
Найти и открыть файл "local.conf"
```
Найти строчку "db = { url = "jdbc:postgresql://localhost:5432/kapinuss", login = "postgres", password = "" }"
и изменить данные БД на свои, т.е данные от вашей локальной БД. Сохранить этот файл.
```
Запустить jar файл с помощью команды "java -jar local3.jar", где local3 - это название вашего файла
```
Развертывание Lib-front:
Открыть консоль и прописать команду
```
git clone https://github.com/stakap/lib-front.git
```
по умолчанию репозиторий скачивается в C:\Users\'Имя Пользователя'\lib-front
проверьте, скачался или нет

Открыть консоль и указать путь до папки 
```
cd C:\Users\'Имя Пользователя'\lib-front
```
И сразу вводим команду npm start
```
C:\Users\vanga\lib-front> npm start
```
Если все получится, то вас автоматически перебросит на сайт 

Развертывание lib-view:
Открыть консоль и прописать команду:
```
"git clone GitHub - stakap/lib-view "
```
Найти в репозитарии файл "build.sbt"
```
Скачать и установить язык скала той версии, которая указана в строке " scalaVersion :="
"Install "
```
Скачать и установить SBT "sbt - Download "
```
Открыть файл "application.conf" в репозитарии lib-view
```
Найти строку db = { url = "jdbc:postgresql://localhost:5432/kapinuss", login = "postgres", password = "" }
и добавить свои лакальные данные БД
```
Запустить lib-view командой "sbt run" и перейти на страницу сайта
```
Откроется страница сайта http://localhost:80 (вместо80 может оказаться другой порт,в зависимости от того, что прописано в конфигурации)

## Авторы проекта
Stanislav - https://github.com/stakap
