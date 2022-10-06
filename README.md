Opencart Turbo
==============

Version: 0.2  
Orignal Code by chrisatomix  
Tweaks from Jay6390  
Continued development by Alex 'Freedom' Haines  
https://www.freedomitsolutions.co.uk  

This script will apply several changes to boost the performance of OpenCart, including:
*   DONE: Converting the MySQL DB Storage Engine from MyISAM to InnoDB.
*   DONE: Adding indexes to all foreign keys (columns ending with '_id') as well as those defined in the script index_list array.
*   DONE: Deleting itself and log file from server on completion (no need to get back into FTP to do this).
*   TODO: Replace config.php and admin/config.php with dynamic Git-friendly version.
*   TODO: Accurately Detect and Remove Demo Data.
*   TODO: Remove Unwanted Zones.
*   BUGS: Script timing issues.

###Notes###
*   This script should be deleted immediately following use.
*   This script should be run again following OpenCart upgrades (as the optimizations will be removed during upgrade).

###Installation###
1.  Upload **turbo.php** to your OpenCart root directory (next to config.php).
2.  Load **https://yoursite/turbo.php** in your browser and follow the instructions on screen.

==============

Этот скрипт применит несколько изменений для повышения производительности OpenCart, в том числе:
* ГОТОВО: Преобразование механизма хранения базы данных MySQL из MyISAM в InnoDB.
* ГОТОВО: Добавление индексов ко всем внешним ключам (столбцы, заканчивающиеся на '_id'), а также к тем, которые определены в массиве index_list скрипта.
* ГОТОВО: Удаление себя и файла журнала с сервера по завершении (для этого не нужно возвращаться на FTP).
* ЗАДАЧА: Заменить config.php и admin/config.php с динамической версией, дружественной к Git.
* ЗАДАЧА: Точное обнаружение и удаление демонстрационных данных.
* ЗАДАЧА: Удалить Ненужные Зоны.
* ОШИБКИ: Проблемы с синхронизацией скрипта.

###Примечания###
* Этот скрипт должен быть удален сразу после использования.
* Этот скрипт следует запустить снова после обновления OpenCart (так как оптимизация будет удалена во время обновления).

###Установка###
1. Загрузить **turbo.php ** в ваш корневой каталог OpenCart (рядом с config.php ).
2. Загрузить **https://ВашСайт/turbo.php ** в вашем браузере и следуйте инструкциям на экране.
