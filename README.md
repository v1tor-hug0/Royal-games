# 🎮 Royal Games API
API desenvolvida em .NET 8 para gerenciamento de dados da loja Royal Games, especializada na compra, venda e troca de videogames, consoles e jogos.
O projeto segue uma arquitetura em camadas, separando responsabilidades para facilitar manutenção, escalabilidade e organização do código.

# 📚 Tecnologias utilizadas: 
C#
.NET 8
ASP.NET Core Web API
Entity Framework Core
SQL Server  
Arquitetura em Camadas
DTO Pattern
Repository Pattern

# 🏗️ Estrutura do Projeto
O projeto está organizado nas seguintes pastas:
RoyalGames
│
├── Applications   → Camada de serviços e regras de negócio
├── Contexts       → Configuração do banco de dados (DbContext)
├── Controllers    → Endpoints da API
├── DTOs           → Objetos de transferência de dados
├── Domains        → Entidades principais do sistema
├── Exceptions     → Tratamento de exceções personalizadas
├── Interfaces     → Interfaces utilizadas no projeto
├── Repositories   → Camada de acesso a dados
│
├── Program.cs     → Configuração principal da aplicação
├── appsettings.json → Configurações da aplicação


# 📡 Endpoints da API
Os endpoints ficam disponíveis através dos Controllers.

Exemplos de operações possíveis:
Criar usuários
Listar jogos
Atualizar informações
Remover registros

Os endpoints podem ser testados usando:
Swagger
Postman
Insomnia

# 🎯 Objetivo do Projeto
Este projeto foi desenvolvido com o objetivo de:
Organizar o sistema da loja Royal Games
Centralizar o gerenciamento de dados
Melhorar o controle de jogos, consoles e usuários
Aplicar boas práticas de desenvolvimento com .NET

# 👨‍💻 Autor
Vitor Hugo

GitHub:
https://github.com/v1tor-hug0
