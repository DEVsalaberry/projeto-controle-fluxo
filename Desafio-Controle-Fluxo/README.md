# DesafioControleFluxo

Este é um projeto Java básico que implementa um sistema de contador com controle de fluxo e exceção customizada para lidar com parâmetros inválidos.

## Funcionalidades

- O programa recebe dois parâmetros via terminal que representam dois números inteiros.
- Realiza a contagem dos números incrementados e imprime no console.
- Lança uma exceção customizada `ParametrosInvalidosException` se o segundo parâmetro for menor ou igual ao primeiro.

## Como Executar

1. Clone este repositório em sua máquina local.
2. Abra o terminal e navegue até o diretório do projeto.
3. Compile o programa com o comando: `javac Contador.java ParametrosInvalidosException.java`
4. Execute o programa com o comando: `java Contador`

Ao executar, o programa solicitará que você digite dois números inteiros. Ele então imprimirá os números incrementados no intervalo especificado.

## Exemplo de Uso

Digite o primeiro parâmetro
5
Digite o segundo parâmetro
10
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5


Caso os parâmetros sejam inseridos de forma inválida (segundo parâmetro menor ou igual ao primeiro), o programa lançará a exceção `ParametrosInvalidosException` com a mensagem "O segundo parâmetro deve ser maior que o primeiro".

## Autor

Este projeto foi desenvolvido por mim como parte do curso "Trilha Java Básico" da Digital Innovation One.

