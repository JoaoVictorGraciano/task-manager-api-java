# Task Manager API - Java Spring Boot

## Descrição
Esta é uma **API de gerenciamento de tarefas** desenvolvida com **Java** e **Spring Boot**. O objetivo é fornecer funcionalidades básicas de gerenciamento de tarefas, como criação, leitura, atualização e exclusão, de forma simples e eficiente. A API também inclui **autenticação de usuários** utilizando **BCrypt**, **validação de dados**, e integração com o banco de dados **H2** para persistência de informações.

## Funcionalidades
- **Cadastro de usuários** com autenticação segura utilizando **BCrypt**.
- **Gerenciamento de tarefas**, incluindo operações de **criar**, **ler**, **atualizar** e **excluir**.
- **Validação de entrada**: como limite de caracteres no título e verificação de datas para garantir que os dados sejam válidos.
- **Integração com banco de dados H2** para persistência dos dados.
- **Tratamento centralizado de exceções** para uma melhor gestão de erros e respostas consistentes.
  
## Tecnologias Utilizadas
- **Java** (JDK 17)
- **Spring Boot** (Framework principal para construção da API)
- **Spring Security** (Para autenticação e segurança dos dados)
- **H2 Database** (Banco de dados embutido, ideal para desenvolvimento)
- **BCrypt** (Para segurança na criptografia de senhas)
- **Maven** (Gerenciador de dependências e build)

## Como Rodar o Projeto

### Pré-requisitos
- **Java 17 ou superior** instalado.
- **Maven** instalado para gerenciamento de dependências e build do projeto.

### Passos para Rodar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seunomeusuario/task-manager-api-java.git
