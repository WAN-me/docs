# Bugs.getcomments

## Описание:
Метод используется для получения коментариев под отчетом о баге

## Параметры:
* accesstoken
* id - идентификатор отчета


## Результат:
После выполнения сервер возвращает массив json-объектов, имеющих следующие поля:
* text - текст коментария
* id - id коментария
* from_id - id автора коментария
* time - число, метка времени
* status - статус(если оставлен)(число от 0 до 11) [статусы](statuses.md)

## Ошибки:
Во время выполнения так же могут возникнуть различные ошибки
* 403,"you are not tester for this product" - возникает при попытке получить отчет из продукта, в котором не состоит пользователь

    Также могут возникать и [ошибки, не связанные с этим методом](errors.md "Список ошибок")

### [Главная](../docs.md "Главная страница документации")