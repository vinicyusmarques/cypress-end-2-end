# Testes _end-to-end_ com Cypress


Projeto com realizado para desevolver e praticar a criação de testes e2e criado pela Talking About Testing para diferentes funcionalidades de uma aplicação web como Sign up, Login e CRUD, e outros como:
- Como otimizar ainda mais o setup de um projeto Cypress heavy_check_mark
- Como analisar estaticamente o código de teste para garantir o uso de convenções definidas pela  comunidade heavy_check_mark
- Como criar testes e2e para diferentes funcionalidades de uma aplicação web, tais como Sign up, Login, CRUD, etc. heavy_check_mark
- Como testar recebimento de e-mails heavy_check_mark
- Como testar upload de arquivos heavy_check_mark
- Como interagir com componentes renderizados dentro de iFrames heavy_check_mark
- Como interceptar requisições para tornar os testes mais robustos heavy_check_mark
- Como proteger dados sensíveis heavy_check_mark
- Como criar testes sem precisar codificar utilizando o Cypress Studio heavy_check_mark
- Como testar a responsividade da aplicação simulando seu uso em um dispositivo móvel - heavy_check_mark
- Como armazenar a sessão do usuário no cache para otimizar o processo de autenticação - heavy_check_mark
- Como criar e documentar comandos customizados heavy_check_mark
- Como configurar um pipeline de integração contínua com múltiplas fases e paralelização - heavy_check_mark
- Como integrar os testes com o Dashboard do Cypress heavy_check_mark
- Como categorizar os testes e executá-los por suas tags heavy_check_mark
- Como documentar um projeto de testes e2e heavy_check_mark
- Como alterar o tema do Test Runner heavy_check_mark

# Testes _end-to-end_ com Cypress

Sample project to demonstrate end-to-end (e2e) tests written with Cypress running on a CI service.

## Pre-requirements

To run this project, you will need:

- [git](https://git-scm.com/downloads) (I've used version `2.26.2` while writing this doc)
- [nodejs](https://nodejs.org/en/) (I've used version `14.17.3` while writing this doc)
- NPM (I've used version `6.14.13` while writing this doc)
- [Google Chrome](https://www.google.com/intl/en_us/chrome/) (I've used version `92.0.4515.131` while writing this doc)

**Note:** When installing nodejs, NPM is automatically installed too.

## Installation

To install the dev dependencies, run `npm install` (or `npm i` for short.)

## Configuring the environment variables

Before running the tests, some environment variables need to be set up.

Make a copy of the [`cypress.env.example.json`](./cypress.env.example.json) file as `cypress.env.json`, and set the appropriate values for all the variables.

**Note:** `cypress.env.json` file is not tracked by git.

## Running the tests

In this project, you can run tests in interactive and headless modes, and on desktop and tablet viewports.

### Headless mode

Run `npm test` (or `npm t` for short) to run all tests in headless mode using a desktop viewport.

Run `npm run test:tablet` to run the appropriate tests in headless mode using a tablet viewport.

### Interactive mode

Run `npm run cy:open` to open the Cypress Test Runner to run tests in interactive mode using a desktop viewport.

Run `npm run cy:open:tablet` to open the Cypress Test Runner to run tests in interactive mode using a tablet viewport.

___

Made with ❤️ by [Vinicyus Marques](https://github.com/vinicyusmarques).

