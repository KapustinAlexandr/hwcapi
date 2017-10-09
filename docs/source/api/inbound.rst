Поступление
===

Метод создаёт ожидаемое поступление.

Адрес
---
::

    /inbound

Метод
---
::

    POST





Параметры
---
.. code-block:: json
    :caption:Пример

    {
        "Owner": "GOGOL",
        "Supplier": "LEGO",
        "Code": "GGL001517",
        "DocumentCode": "15671",
        "DeliveryDate": "2017-07-06T18:25:00.000Z",
        "Rows": 
            [
                {
                    "RowNumber": "1",
                    "Code": "GGL123456",
                    "Quantity": "1",
                    "Price": 1110.56
                },
                {
                    "RowNumber": "2",
                    "Code": "GGL123457",
                    "Quantity": "2",
                    "Price": 6280.77
                }
            ]
    }
    
Успешный ответ
---

Ошибки
---

Пример вызова
---

