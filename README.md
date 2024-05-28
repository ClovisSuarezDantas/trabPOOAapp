# Aplicação de Pagamento

Esta é uma aplicação de exemplo que utiliza o componente de sistema de pagamento. A aplicação permite que o usuário escolha entre diferentes métodos de pagamento e processa o pagamento conforme a escolha do usuário.

## Configuração e Execução

### Requisitos

- Java 8 ou superior
- Maven

### Passo a Passo

1. **Clone o repositório do sistema de pagamento:**

- git clone https://github.com/sua-organizacao/componente-pagamento.git
- cd componente-pagamento
- mvn install

2. Clone este repositório da aplicação:

- git clone https://github.com/sua-organizacao/aplicacao-pagamento.git
- cd aplicacao-pagamento

3. Compile e execute a aplicação:

- mvn clean install
- mvn exec
- Dexec.mainClass="app.AplicacaoPagamento"

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.
