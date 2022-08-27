# go-webserver-exemple
Primeiro código de servidor web escrito em Go

A implementação do servidor é bastante simples. 
Possui uma struct representando os dados a ser retornado e o nome que os campos vão assumir ao serem serializados para JSON. 
O framework web sendo utilizado é o Gin e ele faz esse papel de conversão e envio dos dados através de uma requisição HTTP. 

Para rodar o projeto basta executar os seguintes comandos: 
Comando para baixar as dependências do projeto: 
```
go get .
```
Comando para executar o servidor: 
```
go run . 
```
O servidor irá subir na porta 8000. Será possivel fazer a consulta através do caminho: http://localhost:8000/albums
