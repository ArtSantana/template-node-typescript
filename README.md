# template-node-typescript

O template-node-typescript é um template que contém o setup inicial de um projeto Node com Typescript e Jest.
Tem a função de configurar o eslint, prettier, jest e tsconfig

## Development

### Fazer Download das Dependencias

Para instalar as dependências rodar o comando:

```shell
npm ci
```

### Configuração do editor(VSCode)

É necessário instalar as extensões do ESlint e Prettier em seu vscode.

## Execução

Após instalar as dependências rode o comando:

```shell
npm run build && npm run start;
```

Para utilizar o nodemon rode o comando:

```shell
npm run dev;
```

## Testes Unitários

- Para rodar os testes contidos na pasta tests execute:
  ```shell
  npm run test
  ```
- Para rodar os testes contidos na pasta tests com coverage execute:
  ```shell
  npm run test:coverage
  ```
- Para rodar os testes contidos na pasta tests com watch execute:
  ```shell
  npm run test:watch
  ```
