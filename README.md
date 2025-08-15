# Cypress do Zero à Nuvem

Este projeto tem como objetivo demonstrar, na prática, como utilizar o Cypress para automação de testes end-to-end em aplicações web, desde a configuração inicial até a execução dos testes em ambiente de nuvem.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:

- [Node.js](https://nodejs.org/) (versão recomendada: 14.x ou superior)
- [npm](https://www.npmjs.com/) (geralmente já vem com o Node.js)
- [git](https://git-scm.com/)

## Instalação

Clone o repositório e instale as dependências do projeto:

```bash
git clone <url-do-repositorio>
cd cypress-do-zero-a-nuvem
npm install
```

## Como rodar os testes

Para executar os testes localmente, utilize o comando:

```bash
npx cypress open
```

Ou para rodar em modo headless (sem interface gráfica):

```bash
npx cypress run
```

## Como fazer commit e push para a branch main do seu fork

Após realizar alterações nos arquivos, siga os passos abaixo para fazer commit direto na branch `main` do seu fork e enviar para o GitHub:

```bash
git add .
git commit -m "Descreva aqui a mensagem do commit"
git push origin main
```

Esses comandos vão adicionar todas as alterações, criar um commit e enviar para a branch `main` do seu repositório forkado.

## Outras informações

- Os testes estão localizados na pasta `cypress/e2e`.
- Para configurar variáveis de ambiente, utilize o arquivo `.env`.
- Consulte a [documentação oficial do Cypress](https://docs.cypress.io/) para mais detalhes e customizações.
- Caso encontre problemas, verifique se todos os pré-requisitos estão corretamente instalados.

---
