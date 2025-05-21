# CV Manager API

Esta é uma API de gerenciamento de currículos, desenvolvida em **Go**, utilizando **PostgreSQL** como banco de dados e **GraphQL** para consultas e mutações.

## 🚀 Tecnologias Utilizadas
- **Go** (Golang) - Linguagem de programação principal
- **PostgreSQL** - Banco de dados relacional
- **GraphQL** - API flexível para consultas e mutações
- **GORM** - ORM para interação com PostgreSQL
- **Gin** - Framework HTTP para gerenciamento de rotas

## 📌 Instalação e Configuração

1. **Clone o repositório**
   
   git clone https://github.com/seuusuario/cv-manager.git
   cd cv-manager
   
2. **Configuração do Banco de Dados**

Certifique-se de que o PostgreSQL esteja instalado.

Crie um banco de dados chamado cv_manager.

Configure as credenciais no arquivo .env.

3. **Instale as dependências**

go mod tidy

4. **Inicie o servidor**

go run main.go
