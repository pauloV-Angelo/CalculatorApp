# CalculatorApp

## Descrição

Olá, o **CalculatorApp** é uma aplicação simples de calculadora com interface gráfica desenvolvida em Java utilizando a biblioteca Swing. A calculadora suporta operações básicas como adição, subtração, multiplicação e divisão, além de outras funcionalidades como inversão de sinal, deletar dígitos e limpar a tela. Estou atualmente implementando melhorias nela, como refatoração e tratamento de possíveis erros.

## Objetivo

O objetivo do **CalculatorApp** é simplesmente exercitar conceitos básicos de Java e brincar um pouco com a biblioteca Swing

## Funcionalidades

- **Operações básicas**: Adição, subtração, multiplicação e divisão.
- **Inversão de sinal**: Permite alternar entre valores positivos e negativos.
- **Deletar**: Remove o último dígito inserido.
- **Limpar**: Limpa o display da calculadora.
- **Tratamento de divisão por zero**: Emite uma mensagem de alerta caso uma divisão por zero seja tentada.

## Tecnologias Utilizadas

- Java
- Swing para a interface gráfica

## Como Executar

### Pré-requisitos

- Java JDK instalado na máquina (Java 8 ou superior).

### Passos para Baixar e Executar

1. **Faça um _fork_ do repositório**

   Clique em "Fork" no canto superior direito da página do repositório no GitHub para criar uma cópia do projeto no seu próprio perfil.

2. **Clone o repositório forked**
   ```bash
   git clone https://github.com/seu-usuario/CalculatorApp.git
   ```
   
3. **Navegue até o diretório do projeto**
   ```bash
   cd CalculatorApp
   ```

4. **Compile o código**
   ```bash
   javac src/Calculator.java -d bin
   ```

5. **Execute a aplicação**
   ```bash
   java -cp bin Calculator
   ```

   A calculadora será exibida em uma janela Swing.


## Como Contribuir

Notou algo que pode ser melhorado? Tem alguma sugestão de funcionalidade nova? Fique à vontade para:

- **Abrir uma _issue_**: Descreva o problema ou sugestão.
- **Enviar um _pull request_**: Melhore o código, corrija bugs ou adicione novas funcionalidades.

Toda contribuição é bem-vinda! 😄
