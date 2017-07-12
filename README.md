# Herdeiros Backend

This is a service to get itens needed by Ong Herdeiros and all the events.

## Admistration
To see what's going on with database, manage the stuffs, please go to http://localhost:8000/admin/api/

After log-in, the page will look like this:

![](https://raw.githubusercontent.com/derrix060/HerdeirosBackendDjango/master/sources/admin_webpage.png)

And then, is possible manage the itens to be donated and the events.



## Events
To see all the events, make a GET request to this endpoint: http://localhost:8000/api/eventos/


example of return:
```json
[
    {
        "titulo_text": "Evento Teste", 
        "date_date": "12/07/2017 - 20:51", 
        "local_text": "Rua qualquer, 123", 
        "description_text": "Descricao teste", 
        "image_src_text": ""
    },
    ...
]
```

## Itens needed
To see all the itens needed, make a GET request to this endpoint: http://localhost:8000/api/itens/

example of return:
```json
[
    {
        "name_text": "Refrigerador", 
        "image_src_text": "", 
        "amount": 1
    },
    ...
]
```

