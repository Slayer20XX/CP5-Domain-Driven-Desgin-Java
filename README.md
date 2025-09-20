# CP5-Domain-Driven-Desgin-Java

# Nome e RM:
Matheus Taylor, RM556211

# Nome do Projeto: Sistema de Gerenciamento de Biblioteca Comunitária
# Breve Descrição:
Um sistema de gerenciamento com aplicação web completa, desenvolvida em Spring Boot para gerenciar livros, usuários e empréstimos de uma biblioteca comunitária.

# Funcionalidades Principais:
# Gestão de Livros
- Cadastro de livros com título, autor, ano de publicação e status
- Listagem completa do acervo
- Visualização de livros disponíveis para empréstimo
- Edição e exclusão de registros

# Gestão de Usuários:
- Cadastro de usuários com nome e e-mail
- Listagem de todos os usuários cadastrados

# Controle de Empréstimos:
Registro de novos empréstimos vinculando livros e usuários
Controle de datas de retirada e devolução prevista
Sistema de devolução que atualiza automaticamente o status dos livros
Listagem de empréstimos ativos

# Tecnologias Utilizadas
- Spring Boot - Framework principal
- Spring MVC - Arquitetura web
- Spring Data JPA - Persistência de dados
- Thymeleaf - Template engine para views
- H2 Database - Banco de dados em memória (para desenvolvimento)
- Bootstrap - Interface responsiva
- Validation API - Validações de formulários

# Requisitos Principais:
# Funcionais:
- Cadastro completo de livros (CRUD)
- Cadastro e listagem de usuários
- Sistema de empréstimos com controle de status
- Listagens diversas (todos os livros, disponíveis, empréstimos ativos)

# Técnicos
- Spring Boot com Web, JPA, Thymeleaf e H2
- Validações de formulários
- Interface responsiva com Bootstrap
- Estrutura em camadas (Model, Repository, Controller, View)
