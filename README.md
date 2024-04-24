# goCleanArch
Implementando Clean Architecture com Golang

#baseado no site:
https://dev.to/booscaaa/implementando-clean-architecture-com-golang-4n0a

# A ideia deste projeto é realizar a aplicação dos conhecimentos contidos no site, que fazem referência à

# 1 - Implementação Clean Architecture com Golang
# 2 - Testes unitários com Golang
# 3 - Documentando uma api Go com Swagger



# *First - Implementando Clean Architecture com Golang*
- Será utilizado Arquitetura Hexagonal (Ports and Adapters)

# Requisitos
_Criação de produtos (id, nome, preço e descrição)_
_Listagem de produtos (com paginação no servidor)_

# Usaremos então:

Banco de dados:
PostgresSQL
Libs no go
Pgx: Conexão com o banco de dados
Mux: Roteador de solicitação e um dispatcher para combinar as solicitações recebidas com seus respectivos manipuladores.
Go-paginate: Criação de queries para o postgres
Viper: Configurações para o ambiente de dev/prod
Testify: Teste
Pgx Mock: Mock para o pgx connection pool
Migrate: Rodar as atualizações do nosso banco de dados]





url params
