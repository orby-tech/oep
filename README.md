# OWS Events - Парсинг
Данный репозиторий содержит в себе часть проекта [ows-events](https://github.com/openworld-community/ows-events) отвечающая за скрейпинг и парсинг данных о мероприятиях с различных интернет-ресурсов
# Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)

## Installation
Для локальной установки следуйте данной инструкции
1. Скачайте репозиторий
2. Находясь в корневом фолдере проекта запустите команду
```python
docker-compose up --build
```

## Usage
Для проверки работы парсеров используйте get запрос
```python
http://127.0.0.1:8080/api/standalone/{имя парсера}
```
Имена парсеров:
* visityerevan - для парсера по сайту https://www.visityerevan.am/
* belgrad_consult_com - для парсера по сайту https://belgrad-consult.com/afisha-belgrada
* batumifun - для парсера по сайту https://batumi.fun/
# Важная информация
- Данная инструкция написана для пользователей os Windows, если у вас не получилось запустить проект на системах Mac и Linux просим вас написать об этом в дискорд в ветку "Парсинг"
- Также стоит сказать что вы можете увидеть ещё один endpoint по Белграду. Было принято решение переписать его, поэтому его запрос пока не работает.