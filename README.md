# Calculadora em React

Este repositório contém uma aplicação de calculadora simples desenvolvida em React. A aplicação permite realizar operações básicas de adição e subtração, além de implementar uma interface amigável.

## Estrutura do Projeto

### 1. Componentes

#### a. `App.js`

Este é o componente principal da aplicação, onde gerenciamos o estado da calculadora e as operações.

- **Estado:**
  - `currentNumber`: Representa o número que está sendo digitado atualmente.
  - `firstNumber`: Armazena o primeiro número digitado para operações.
  - `operation`: Armazena a operação atual (adição ou subtração).

- **Funções principais:**
  - `handleOnClear()`: Reseta a calculadora.
  - `handleAddNumber(num)`: Adiciona um número ao `currentNumber`.
  - `handleSumNumbers()`: Realiza a soma entre `firstNumber` e `currentNumber`.
  - `handleMinusNumbers()`: Realiza a subtração entre `firstNumber` e `currentNumber`.
  - `handleEquals()`: Executa a operação escolhida quando o usuário clica no botão de igual.

### 2. Estilos Globais

#### a. `global.js`

Define os estilos globais da aplicação usando `styled-components`.

- **Estilos:**
  - Remove margens e paddings de todos os elementos.
  - Define uma cor de fundo padrão para a aplicação.

### 3. Estilos de Container

#### a. `styles.js`

Contém os componentes estilizados para a estrutura da aplicação.

- **Componentes:**
  - `Container`: Um contêiner que ocupa toda a altura da tela e centraliza os elementos.
  - `Content`: Um contêiner interno que serve como fundo para a calculadora.
  - `Row`: Um componente que organiza os botões em linhas.
  - `Column`: Um componente que organiza elementos em colunas.

### 4. Componente de Entrada

#### a. `Input.js`

Um componente que exibe o número atual que está sendo digitado na calculadora.

### 5. Componente de Botão

#### a. `Button.js`

Um componente reutilizável para criar os botões da calculadora.

### Exemplo de Uso

O componente `App` é o coração da aplicação. Ao rodar a aplicação, o usuário verá uma interface com botões para números e operações. Aqui está um exemplo de como a interação funciona:

1. O usuário clica em um número (por exemplo, `5`).
2. O usuário clica em uma operação (por exemplo, `+`).
3. O usuário clica em outro número (por exemplo, `3`).
4. O usuário clica em `=` para obter o resultado.

## Autor

**Feito por Railton Araujo.**
