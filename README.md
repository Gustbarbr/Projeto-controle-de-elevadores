# Seja bem-vindo ao projeto de Controle de Elevadores!

## Objetivo do nosso projeto
* Este projeto consiste na modelagem de um novo sistema para controle de elevadores para uma rede de hoteis utilizando UML para realizar a modelagem.
### Os requisitos do projeto
1. Todo o controle deve ser realizado a partir de uma sala de comando.
2. O acesso ao sistema de controle deve ser individualizado. O Usuário master pode gerenciar os usuários do sistema de controle, com seu respectivo nível de autorização.
3. Todas as ações de comando de controle devem ser registradas em logs auditáveis.
4. A chamado dos elevadores é feita através de
botoeira externa, onde os usuários selecionam
o andar desejado.
5. Cada unidade da rede possui uma quantidade
diferente de elevadores.
6. Unidades com mais de 20 andares dividem o
serviço por elevador. Por exemplo, primeiras
10 andares são atendidos pelos elevadores A e
B e os últimos 10 andares, pelos elevadores C
e D. Tudo isso deve ser configurável na Sala de
Comando.
7. Alguns hotéis podem contar com andares VIP,
onde o acesso ao andar é permitido
exclusivamente através de reconhecimento
fácil pela câmera do próprio elevador.
8. Cada elevador possui um display interno,
indicando o andar em que está e os andares em
que vai parar.
9. No lado externo de cada elevador há indicador
de sentido (subindo ou descendo) e do andar
em que ele está.
10. Caso seja identificada uma situação de
incêndio, todos os elevadores devem
imediatamente se direcionar ao térreo e abrir
as portas.
11. Outras emergências o elevador deve se
direcionar ao andar mais próximo e parar,
abrindo as portas. Assim que todos os
passageiros saírem as portas devem ser
fechadas e o elevador permanecer parado.
12. Os elevadores devem possuir controle de carga
máxima e, caso seja excedida a capacidade
máxima de carga, o mesmo deve emitir um
aviso e parar a operação até que a situação seja
regularizada.
13. Exibir Data/hora do último login dos usuários
controladores.
## Aonde consultar e visualizar os diagramas
* Todos os diagramas em UML podem ser encontrados acessando nossa [wiki](https://github.com/Gustbarbr/Projeto-controle-de-elevadores/wiki).
