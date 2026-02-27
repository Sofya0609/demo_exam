1). Инициализировать контейнеры в Docker Compose
```powershell
docker compose build
```
2). Поднять контейнеры
```powershell
docker compose up
```
3). Основной сайт располагается по `http://localhost:8080/`
Существует пользователь
Логин:qwer@qebghnj.gt
Пароль: 123456789

4). phpmyadmin располгается по `http://localhost:8081/`
Пользователь: yii2user
Пароль: yii2password

5). Для корректной работы нужно выполнить код из dump 
Это можно сделать в phpmyadmin, выбрать базу данных и нажать импорт, указав `yii2advanced.sql`

6). Вход в админку:http://localhost:8080/admin.html
Логин: Admin26
Пароль: Demo20
