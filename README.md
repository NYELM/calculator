### Português abaixo do inglês

# Calculator

This repository contains a simple calculator implemented using HTML, CSS, and JavaScript.

## Usage

To use the calculator, follow these steps:

1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. The calculator interface will be displayed, allowing you to perform calculations.

## Features

- The calculator has a text input field with the ID "resultado" to display the entered numbers and calculation results.
- The calculator includes various buttons for performing different actions:
  - Numeric buttons (0-9): Clicking these buttons appends the corresponding number to the input field.
  - Operator buttons (+, -, *, /): Clicking these buttons appends the corresponding operator to the input field.
  - Special buttons:
    - "C" (Clear): Clicking this button clears the input field.
    - "=" (Equal): Clicking this button evaluates the expression in the input field and displays the result in the input field.

## Styling

The calculator is styled using Bootstrap, a popular CSS framework. The styling includes a dark color scheme, rounded corners, and box shadows.

## JavaScript Function

The script section at the bottom of the HTML file contains a JavaScript function called `calcular`. This function is responsible for handling button clicks and performing the corresponding actions based on the button type and value.

- If the button type is "acao", the function checks the button value and performs the following actions:
  - If the value is "c" (Clear), it clears the input field by setting its value to an empty string.
  - If the value is one of the operators (+, -, *, /, or .), it appends the operator to the input field.
  - If the value is "=" (Equal), it evaluates the expression in the input field using the `eval` function and displays the result in the input field.
- If the button type is "valor", the function appends the button value (numeric or decimal point) to the input field.

## Contribution

This project is just a simple demonstration and is not open for contributions at the moment.

### English below

# Calculadora

Este repositório contém uma calculadora simples implementada usando HTML, CSS e JavaScript.

## Uso

Para utilizar a calculadora, siga os passos abaixo:

1. Clone o repositório em sua máquina local.
2. Abra o arquivo `index.html` em um navegador web.
3. A interface da calculadora será exibida, permitindo que você faça cálculos.

## Recursos

- A calculadora possui um campo de texto com o ID "resultado" para exibir os números inseridos e os resultados dos cálculos.
- A calculadora inclui vários botões para realizar diferentes ações:
  - Botões numéricos (0-9): Ao clicar nesses botões, o número correspondente será adicionado ao campo de texto.
  - Botões de operadores (+, -, *, /): Ao clicar nesses botões, o operador correspondente será adicionado ao campo de texto.
  - Botões especiais:
    - "C" (Limpar): Ao clicar neste botão, o campo de texto será limpo.
    - "=" (Igual): Ao clicar neste botão, a expressão no campo de texto será avaliada e o resultado será exibido no campo de texto.


## Estilo

A calculadora utiliza o Bootstrap, um framework CSS popular, para estilização. O estilo inclui um esquema de cores escuro, cantos arredondados e sombras.

## Função JavaScript

A seção de script no final do arquivo HTML contém uma função JavaScript chamada `calcular`. Essa função é responsável por lidar com os cliques nos botões e realizar as ações correspondentes com base no tipo e valor do botão.

- Se o tipo do botão for "acao", a função verifica o valor do botão e realiza as seguintes ações:
  - Se o valor for "c" (Limpar), o campo de texto será limpo, definindo seu valor como uma string vazia.
  - Se o valor for um dos operadores (+, -, *, / ou .), o operador será adicionado ao campo de texto.
  - Se o valor for "=" (Igual), a expressão no campo de texto será avaliada usando a função `eval` e o resultado será exibido no campo de texto.
- Se o tipo do botão for "valor", a função adiciona o valor do botão (numérico ou ponto decimal) ao campo de texto.

## Contribuição

Este projeto é apenas uma demonstração simples e não está aberto para contribuições no momento.
