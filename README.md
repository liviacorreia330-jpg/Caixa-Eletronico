Caixa Eletrônico – Simulador de Saque

Este programa simula o funcionamento de um caixa eletrônico, calculando automaticamente a quantidade de notas necessárias para realizar um saque a partir de um valor informado pelo usuário.

Como funciona

O programa exibe o título “Caixa Eletrônico” e solicita que o usuário digite um valor inteiro para saque, com valor mínimo de R$ 2. Se o valor digitado for menor que R$ 2, o programa informa que o valor é inválido e o saque não é realizado.

Se o valor for válido, o programa calcula a quantidade de cada nota necessária para compor o saque. As notas disponíveis são R$ 100, R$ 50, R$ 20, R$ 10, R$ 5 e R$ 2. A lógica utiliza divisões inteiras para determinar o número de notas e atualiza o valor restante a cada etapa.

Ao final, o programa exibe apenas as notas que serão entregues, omitindo aquelas com quantidade zero.

Exemplo de uso

O usuário pode digitar um valor, como R$ 186, e o programa exibirá:
Saque realizado com sucesso
Notas de 100: 1
Notas de 50: 1
Notas de 20: 1
Notas de 10: 1
Notas de 5: 1

Requisitos

Para executar o programa é necessário ter o Python 3 instalado e utilizar um terminal ou IDE que permita entrada de dados pelo teclado.
