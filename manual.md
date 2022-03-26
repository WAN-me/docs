# Инструкция по использованию апи

## Запросы
Для связи с api можно использовать POST и GET запросы. Все запросы следует отправлять либо на api.wan-group.ru(Рекомендуемо) либо на wan-group.ru:5000

Большинство действий с апи - это вызов методов. Для вызова метода нужно передать его название на страницу __api.wan-group.ru/method__ передав имя метода в адресной строке. Например api.wan-group.ru/method?method=users.get&<...>

    Пример кода на python:


```python
    import json,requests
    ...
    def rget(method:str,params:dict):
        r = requests.get("https://api.wan-group.ru/method/"+method,params)
        try:
            return json.loads(r.content.decode('utf-8'))
        except:
            print(r.content)

```

### [Главная](docs.md "Главная страница документации")