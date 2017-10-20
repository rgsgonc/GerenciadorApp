# LOCALHOST

CURL (Login)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"usuario":"rafael","senha":"123456"}' http://localhost:8080/GerenciadorFinanceiro/rest/login/autenticacao

# CURL (Cadastro Categoria)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"nomeCategoria":"Alimentacao"}' http://localhost:8080/GerenciadorFinanceiro/rest/categoria/cadastro

► GET: curl http://localhost:8080/GerenciadorFinanceiro/rest/categoria/listarCategorias

# CURL (Cadastro de Receita)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"data":"15/09/2017","descricao":"balada com amigos", "valor":"150,00"}' http://localhost:8080/GerenciadorFinanceiro/rest/receita/cadastro

► GET: curl http://localhost:8080/GerenciadorFinanceiro/rest/receita/listarReceitas

# CURL (Cadastro de Despesa)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"data":"15/10/2017","descricao":"mecanico", "valor":"350,00"}' http://localhost:8080/GerenciadorFinanceiro/rest/despesa/cadastro

► GET: curl http://localhost:8080/GerenciadorFinanceiro/rest/despesa/listarDespesas

# CURL (Cadastro de Cartão)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"id":"1", "numero":"12345678","dataValidade":"18/09/2017","codigoSeguranca":"321","nomeTitular":"Rafael Santos"}' http://localhost:8080/GerenciadorFinanceiro/rest/cartao/cadastro

► GET: curl http://localhost:8080/GerenciadorFinanceiro/rest/cartao/listarCartoes

# CURL (Cadastro de Usuário)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"id":"1","nome":"rafa", "endereco":"rua praca XV", "email":"rgs.gonc@gmail.com", "telefone":"99151767", "senha":"123456", "confirmaSenha":"123456"}' http://localhost:8080/GerenciadorFinanceiro/rest/usuario/cadastro

► GET: curl http://localhost:8080/GerenciadorFinanceiro/rest/usuario/listarUsuario 

# TOMCAT RAFAEL

CURL (Login)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"usuario":"rafael","senha":"123456"}' http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/login/autenticacao

# CURL (Cadastro Categoria)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"nomeCategoria":"Alimentacao"}' http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/categoria/cadastro

► GET: curl http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/categoria/listarCategorias

# CURL (Cadastro de Receita)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"data":"15/09/2017","descricao":"balada com amigos", "valor":"150,00"}' http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/receita/cadastro

► GET: curl http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/receita/listarReceitas

# CURL (Cadastro de Despesa)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"data":"15/10/2017","descricao":"mecanico", "valor":"350,00"}' http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/despesa/cadastro

► GET: curl http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/despesa/listarDespesas

# CURL (Cadastro de Cartão)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"id":"1", "numero":"12345678","dataValidade":"18/09/2017","codigoSeguranca":"321","nomeTitular":"Rafael Santos"}' http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/cartao/cadastro

► GET: curl http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/cartao/listarCartoes

# CURL (Cadastro de Usuário)
► POST: curl -H "Content-Type: application/json" -X POST -d '{"id":"1","nome":"rafa", "endereco":"rua praca XV", "email":"rgs.gonc@gmail.com", "telefone":"99151767", "senha":"123456", "confirmaSenha":"123456"}' http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/usuario/cadastro

► GET: curl http://35.199.24.34/GerenciadorFinanceiroRafaelGuilherme/rest/usuario/listarUsuario 
