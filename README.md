# 🚚 API de Entregas

Esta é uma API de **Entregas** construída com **Node.js**, **Express.js**, **Docker**, **Zod** e **Jest** para gerenciamento e controle de entregas. Ela permite registrar, atualizar e consultar status de entregas de forma simples e eficiente.

## 🛠 Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript no lado do servidor.
- **Express.js**: Framework minimalista para criar APIs e servidores web.
- **Docker**: Ferramenta para criar, implantar e executar aplicativos em containers.
- **Zod**: Biblioteca para validação de dados e schemas.
- **Jest**: Framework de testes para garantir que a API funcione corretamente.

## 🚀 Funcionalidades

- **Criar uma entrega**: Registra uma nova entrega com detalhes como, status e previsão de entrega.
- **Listar entregas**: Obtém uma lista com todas as entregas registradas.
- **Atualizar status da entrega**: Permite alterar o status de uma entrega (ex: "Em trânsito", "Entregue").
- **Validar dados**: Utiliza o Zod para garantir que os dados enviados na requisição estão corretos.

## 📦 Como Rodar o Projeto

### 1. Clone o Repositório

Primeiro, faça o clone do repositório para a sua máquina local:

```bash
git clone https://github.com/alissonsveen/rocketlog
cd rocketlog
npm install
docker-compose up
