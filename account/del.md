# Acсount.del

## Описание:
Метод позволяет удалить пользователя из базы данных. ВНИМАНИЕ!!! после выполнения данного метода все данные о пользователе будут стёрты с диска БЕЗВОЗВРАТНО! Никто кроме вас самих не несет ответственность за совершённое удаление.

## Параметры:
* accesstoken

## Результат:
После выполнения сервер возвращает json-объект, имеющий следующие поля:
* state = "ok" - в случае, если удаление пользователя прошло успешно

## Ошибки:
Во время выполнения могут возникать [ошибки, не связанные с этим методом](../errors.md "Список ошибок")

### [Главная](../docs.md "Главная страница документации")