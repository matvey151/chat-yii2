Yii 2 Chat Project
===============================
 2 контроллера
-----------------------------------
1. frontend\controllers\ShowmodalController

   отвечает за регистрацию, логинизацию, вывод загруженных файлов

2. frontend\controllers\SiteController

   отвечает за отображение чата, logout, и взаимодействует с виджетом

 2 модели :
--------------------------------
1.frontend\models\Chat
2.frontend\models\User

Чат выполнен в виде виджета
------------------------------

1.common\widgets\ChatRoom


не выполнил сохранение данных в файлы

DIRECTORY STRUCTURE
-------------------


db_dump
--------------------------------------------------------------------------------------------
    yii-advanced.sql                дамп базы

frontend
----------------------------------------------------------------------------------------------
    config/main-local.php           настройки для доступа к базу
    web/index.php                   входной скрипт в приложение


