# web_application
# Delphi WebBroker IIS Application

## Требования
- Delphi 10.4+
- Microsoft IIS с модулем CGI
- MSSQL Server

## Настройка
1. Склонируйте репозиторий
2. Откройте `Project1.dproj` в Delphi
3. Настройте `ADOConnection1` на вашу БД(sql скрипт в библиотеке - Library_db)
4. Активируйте 'ADOQuery1', 'DataSetTableProducer', и установите все связи между инструментами
5. Скомпилируйте проект
6. Скопируйте `.exe` и `web.config` в папку IIS

## Описание
Веб-приложение показывает список различных книг с подробной информацией
