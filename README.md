# Лабораторная 03. Java Servlet

Нужны JDK 21, Maven 3.9 и Apache Tomcat 10.1. Из корня проекта выполните `mvn clean package`.
Скопируйте `target/lab03.war` в папку `webapps` Tomcat, запустите сервер и откройте [приложение](http://localhost:8080/lab03/).

Стартовая HTML-форма передаёт name через GET. Сервлет также поддерживает POST и параметр инициализации heading.
