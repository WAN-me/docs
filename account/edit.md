# Accounts.edit

## Описание:
Метод используется для изменения данных своего аккаунта 

## Параметры:
* accesstoken
* name - новое имя пользователя
* image - ссылка на изображение профиля пользователя( может так же содержать *default.png*) [Список поддерживаемых типов изображений](../account/image_types.md "Перейти")

## Результат:
После выполнения сервер возвращает json-объект, имеющий следующие поля:
* state = "ok" - в случае, если редактированние прошло успешно

## Ошибки:

Во время выполнения могут возникать [ошибки, не связанные с этим методом](../errors.md "Список ошибок")

### [Главная](../docs.md "Главная страница документации")