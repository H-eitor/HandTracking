# RelatóriodaMissãoHand Tracking

## Descrição

O projeto consiste na utilização das bibliotecas OpenCv e MediaPipe para
processamento das imagens da webcam com o objetivo de reconhecer números através
dos dedos das mãos.
Por falta de compatibilidade da biblioteca com as versões atuais de python,o projeto
foi realizado no python 3.7.0.

## Resultado

O sistema de numeração utilizado consiste no sistema binário, onde cada dedo
representa um bit, permitindo assim a contagem de 0 a 31 utilizando apenas uma mão. O
funcionamento do código requer a utilização apenas da mão esquerda, com a palma virada
em direção à câmera.

 Segue uma tabela representando as possíveis combinações numéricas:

![Tabela de possíveis combinações](./img/Captura%20de%20tela%202025-01-28%20122903.png)

 Seguem abaixo exemplos do código em funcionamento:

![Captura de tela com o número 18](./img/Captura%20de%20tela%202025-01-28%20122923.png "18")
![Captura de tela com o número 7](./img/Captura%20de%20tela%202025-01-28%20122932.png "7")
![Captura de tela com o número 25](./img/Captura%20de%20tela%202025-01-28%20122940.png "25")
![Captura de tela com o número 31](./img/Captura%20de%20tela%202025-01-28%20122950.png "31")