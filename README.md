# ELK FILEBEAT Тестовое задание

У вас должен быть установлен docker-compose

### Компоненты стека:

- **Elasticsearch**: Хранилище данных для индексации и поиска логов.
- **Kibana**: Веб-интерфейс для визуализации данных из Elasticsearch.
- **Logstash**: Посредник для обработки логов, принимает их от Filebeat, разбирает и отправляет в Elasticsearch.
- **Filebeat**: Легкий агент для пересылки логов, считывает их из файла и передает в Logstash.

Выполните следующие команды в каталоге `docker-compose up -d`:

*Дальше открываем Kibana**:


- **Kibana**: Доступен по URL: `http://localhost:5601`. Откройте веб-интерфейс Kibana для визуализации и анализа данных.


Заходим дальше в Index Pattern
![Index](https://github.com/Rabbit1430/testdocker/blob/main/1.jpg)
Создаем Pattern

![Index](https://github.com/Rabbit1430/testdocker/blob/main/2.jpg)

![Index](https://github.com/Rabbit1430/testdocker/blob/main/3.jpg)


И потом заходим в Discover и все фильтруем что нужно и отображаем
