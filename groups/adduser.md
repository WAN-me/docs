# Groups.adduser

## Описание:
Метод позволяет добавить пользователя в группу, требудется id пользователя и группы

## Параметры:
* accesstoken
* user_id - id пользователя
* id - id группы 

## Результат
После выполнения сервер возвращает json-объект, имеющий следующие поля:
* state = "ok" - в случае, если добавление прошло успешно

## Ошибки:
Во время выполнения  могут возникнуть различные ошибки
* 403,"access denided for this group" - возникает, если группа не открыта для вступления

* Также могут возникать и [ошибки, не связанные с этим методом](../errors.md "Список ошибок") 



### [Главная](../docs.md "Главная страница документации")