# LOCALHOST

## LOGIN
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Login|curl -H "Content-Type: application/json" -X POST -d '{"usuario":"rafael","senha":"123456"}' http://localhost:8080/GerenciadorFinanceiro/rest/login/autenticacao| ✔ | ✔ 

## CADASTRO CATEGORIA
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Cadastro Categoria|curl -H "Content-Type: application/json" -X POST -d '{"id":"1","nomeCategoria":"Alimentacao"}' http://localhost:8080/GerenciadorFinanceiro/rest/categoria/cadastro| ✔ | ✔
|GET|Cadastro Categoria|curl http://localhost:8080/GerenciadorFinanceiro/rest/categoria/buscar/1| ✔ | ✔
|PUT|Cadastro Categoria|curl -X PUT -H "Content-Type: application/json" -d '{"id":"1","nomeCategoria":"Gasolina"}' http://localhost:8080/GerenciadorFinanceiro/rest/categoria/editar| ✔ | ✔
|DELETE|Cadastro Categoria|curl -X DELETE http://localhost:8080/GerenciadorFinanceiro/rest/categoria/delete/1| ✔ | ✔

## CADASTRO DE RECEITA
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Cadastro de Receita|curl -H "Content-Type: application/json" -X POST -d '{"id":"1","data":"01/12/2017","descricao":"desenv software","valor":"3500"}' http://localhost:8080/GerenciadorFinanceiro/rest/receita/cadastro| ✔ | ✔
|GET|Cadastro de Receita|curl http://localhost:8080/GerenciadorFinanceiro/rest/receita/buscar/1| ✔ | ✔
|PUT|Cadastro de Receita|curl -X PUT -H "Content-Type: application/json" -d '{"id":"1","data":"01/12/2017","descricao":"desenv software","valor":"6500"}' http://localhost:8080/GerenciadorFinanceiro/rest/receita/editar| ✔ | ✔
|DELETE|Cadastro de Receita|curl -X DELETE http://localhost:8080/GerenciadorFinanceiro/rest/receita/delete/1| ✔ | ✔

## CADASTRO DE DESPESA
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Cadastro de Despesa|curl -H "Content-Type: application/json" -X POST -d '{"data":"15/10/2017","descricao":"mecanico", "valor":"350,00"}' http://localhost:8080/GerenciadorFinanceiro/rest/despesa/cadastro| ✔ | ✖
|GET|Cadastro de Despesa|curl http://localhost:8080/GerenciadorFinanceiro/rest/despesa/listarDespesas| ✔ | ✖

## CADASTRO DE CARTÃO
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Cadastro de Cartão|curl -H "Content-Type: application/json" -X POST -d '{"id":"1","numero":"123456", "dataValidade":"10/2020", "codigoSeguranca":"123", "nomeTitular":"Rafael Santos"}' http://localhost:8080/GerenciadorFinanceiro/rest/cartao/cadastro| ✔ | ✔
|GET|Cadastro de Cartão|curl http://localhost:8080/GerenciadorFinanceiro/rest/cartao/buscar/1| ✔ | ✔
|PUT|Cadastro de Cartão|curl -X PUT -H "Content-Type: application/json" -d '{"id":"1","numero":"55555", "dataValidade":"10/2020", "codigoSeguranca":"123", "nomeTitular":"Rafael Santos"}' http://localhost:8080/GerenciadorFinanceiro/rest/cartao/editar| ✔ | ✔
|DELETE|Cadastro de Cartão|curl -X DELETE http://localhost:8080/GerenciadorFinanceiro/rest/cartao/delete/1| ✔ | ✔

## CADASTRO DE USUÁRIO
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Cadastro de Usuário|curl -H "Content-Type: application/json" -X POST -d '{"id":"1","nome":"rafael", "endereco":"rua praca XV", "email":"rgs.gornc@gmail.com", "telefone":"99151767", "senha":"123456"}' http://localhost:8080/GerenciadorFinanceiro/rest/usuario/cadastro| ✔ | ✔
|GET|Cadastro de Usuário|curl http://localhost:8080/GerenciadorFinanceiro/rest/usuario/buscar/1| ✔ | ✔
|PUT|Cadastro de Usuário|curl -X PUT -H "Content-Type: application/json" -d '{"id":"1","nome":"agora eh maria", "endereco":"rua praca XV", "email":"rgs.gornc@gmail.com", "telefone":"99151767", "senha":"123456"}' http://localhost:8080/GerenciadorFinanceiro/rest/usuario/editar| ✔ | ✔
|DELETE|Cadastro de Usuário|curl -X DELETE http://localhost:8080/GerenciadorFinanceiro/rest/usuario/delete/1| ✔ | ✔

# TOMCAT RAFAEL
## LOGIN
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Login|curl -H "Content-Type: application/json" -X POST -d '{"usuario":"rafael","senha":"123456"}' http://35.199.24.34/GerenciadorFinanceiro/rest/login/autenticacao| ✔ | ✔ 

## CADASTRO CATEGORIA
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Cadastro Categoria|curl -H "Content-Type: application/json" -X POST -d '{"nomeCategoria":"Alimentacao"}' http://35.199.24.34/GerenciadorFinanceiro/rest/categoria/cadastro| ✔ | ✔
|GET|Cadastro Categoria|curl http://35.199.24.34/GerenciadorFinanceiro/rest/categoria/listarCategorias| ✔ | ✔

## CADASTRO DE RECEITA
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Cadastro de Receita|curl -H "Content-Type: application/json" -X POST -d '{"data":"15/09/2017","descricao":"balada com amigos", "valor":"150,00"}' http://35.199.24.34/GerenciadorFinanceiro/rest/receita/cadastro| ✔ | ✔
|GET|Cadastro de Receita|curl http://35.199.24.34/GerenciadorFinanceiro/rest/receita/listarReceitas| ✔ | ✖

## CADASTRO DE DESPESA
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Cadastro de Despesa|curl -H "Content-Type: application/json" -X POST -d '{"data":"15/10/2017","descricao":"mecanico", "valor":"350,00"}' http://35.199.24.34/GerenciadorFinanceiro/rest/despesa/cadastro| ✔ | ✖
|GET|Cadastro de Despesa|curl http://35.199.24.34/GerenciadorFinanceiro/rest/despesa/listarDespesas| ✔ | ✖

## CADASTRO DE CARTÃO
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Cadastro de Cartão|curl -H "Content-Type: application/json" -X POST -d '{"id":"1", "numero":"12345678","dataValidade":"18/09/2017","codigoSeguranca":"321","nomeTitular":"Rafael Santos"}' http://35.199.24.34/GerenciadorFinanceiro/rest/cartao/cadastro| ✔ | ✖
|GET|Cadastro de Cartão|curl http://35.199.24.34/GerenciadorFinanceiro/rest/cartao/listarCartoes| ✔ | ✖

## CADASTRO DE USUÁRIO
|Método |Tela| CURL | Testado | Tela Android
|------ |------ | ------ | ------ | ------ |
|POST|Cadastro de Usuário|curl -H "Content-Type: application/json" -X POST -d '{"id":"1","nome":"rafa", "endereco":"rua praca XV", "email":"rgs.gonc@gmail.com", "telefone":"99151767", "senha":"123456", "confirmaSenha":"123456"}' http://35.199.24.34/GerenciadorFinanceiro/rest/usuario/cadastro| ✔ | ✔
|GET|Cadastro de Usuário|curl http://35.199.24.34/GerenciadorFinanceiro/rest/usuario/listarUsuario| ✖ | ✔
