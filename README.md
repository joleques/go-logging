# Custom Log com go-chi

- POC para gerar logs customizados que podem ser enviados ao elasticsearch

# Run

```
go run main.go
```


## API

- Welcome: Log padrão

``` 
Url: http://localhost:3000/
Method: GET
Content-Type: application/json

Response: welcome
```

- Wait: Exemplo de como add um field no log que vai ser gerado

``` 
Url: http://localhost:3000/wait
Method: GET
Content-Type: application/json

Response: hi
```

- Panic: Exemplo de log com stacktrace do erro

``` 
Url: http://localhost:3000/wait
Method: GET
Content-Type: application/json
```