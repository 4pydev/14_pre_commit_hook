# Автозапуск тестов с pre-commit

При использовании скрипта pre-commit (см. ниже) при попытке коммита будет запускаться проверка всех .py файлов в корне проекта на соответствие стандартам PEP8, а также тесты из файла tests.py. 

Коммит будет выполнен только в случае успешного завершения всех тестовых мероприятий.

# Как использовать

Файл pre-commit переместить в папку ./.git/hooks.

При необходимости сделать файл исполняемым:
```bash
$ sudo chmod +x pre-commit
```