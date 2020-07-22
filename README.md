# Инструкции по установке и настройке
## Установка
1. Устанавливаем через Composer:
    * Команда: **composer create-project evolutioncms/evolution:2.0.x .**  
        * В конце обязательно должна быть точка, чтобы установить в текущую дерикторию
        * Дериктория должная быть обязательно пустая, чтобы не было конфликтов с composer
2. Устанавливаем сам движок (в командной строке)
    * Команда **php install/cli-install.php [параметры]**
    * Например: **php install/cli-install.php --database_server=localhost --database=DB --database_user=USER --database_password=PASS --cmsadmin=admin --cmsadminemail=email@email.ru --cmspassword=password --language=ru --mode=new --installData=n --removeInstall=y**
        * database_server=localhost (сервер базы данных)
        * database=DB (имя базы данных)
        * database_user=USER (имя пользователя базы данных)
        * database_password=PASS (пароль базы данных)
        * [table_prefix=evo_] (префикс таблиц (тут есть встроенный генератор префиксов, поэтому параметр не обязательный))
        * cmsadmin=admin (имя пользователя администратора)
        * cmsadminemail=email@gmail.com (почта администратора)
        * cmspassword=123456 (пароль администратора)
        * language=ru (язык системы управления)
        * mode=new 
        * installData=n (установить начальный шаблон)
        * removeInstall=y (удалить папку с установкой после установки)
## Настройка после установки
После установки система управления предложит настроить ее. В целом можно ничего не менять и оставить как есть. 
**Это не влияет на работоспособность!**
