# Лабораторные работы по БСБД

## Модули
- [Модуль 1](https://github.com/DBS-UTMN/PT-21/tree/main/module_1) - Создание структуры БД, нормализация, ограничения целостности
- [Модуль 2](https://github.com/DBS-UTMN/PT-21/tree/main/module_2) - Внешние таблицы, функции, вычесляемые столбцы, партицирование
- [Модуль 3](https://github.com/DBS-UTMN/PT-21/tree/main/module_3) - Индексы, представления, планы запросов, статистика
- [Модуль 4](https://github.com/DBS-UTMN/PT-21/tree/main/module_4) - Уровни изоляции, репликация данных
- [Модуль 5](https://github.com/DBS-UTMN/PT-21/tree/main/module_5) - Аудит, RLS, SQL-иньекции

## Полезные ссылки

- [DBeaver](https://dbeaver.io/download/) - Утилита для работы с базой данных (поддержка большинства популярных движков СУБД)!
- [Docker desktop](https://www.docker.com/products/docker-desktop/) - Утилита для запуска и управления контейнера в среде Windows
- [VS Code](https://code.visualstudio.com/Download) - IDE с поддержкой большинства современных языков программирования и наличием огромного количества расширений.

## Запуск контейнеров 
```sh
cd module_${номер_модуля}
docker compose . up -d
```
Логины и пароли будут указаны в docker-compose файле или подробнее будет указано в самом модуле.


