- [Caso de Uso Geral](#caso-de-uso-geral)
- [Visão de Classe Participantes](#visão-de-classe-participantes)
    - [Comprar Produto](#comprar-produto)
    - [Lançar Produto](#lançar-produto)
    - [Realizar Cadastro](#realizar-cadastro)
    - [Realizar Devolução](#realizar-devolução)
    - [Visualizar Rastreio](#visualizar-rastreio)
- [Diagramas de Sequência](#diagramas-de-sequência)
    - [Lançar Produto](#lançar-produto-2)
    - [Realizar Compra](#realizar-compra-2)
    - [Visualizar Rastreio](#visualizar-rastreio-2)
- [Diagramas de Estado](#diagramas-de-sequência)
    - [Estados do Pedido](#estados-pedido)
    - [Estados do Produto](#estados-produto)
- [Diagramas de Atividade](#diagramas-de-atividade)
    - [Avaliar Produto](#avaliar-produto)
    - [Realizar Compra](#realizar-compra-3)
## Caso de Uso Geral

O modelo de casos de uso (MCU) é uma representação das *funcionalidades* externamente observáveis do sistema e dos *elementos exeternos* ao sistema que interagem com ele. O MCU é um modelo de análise que representa um refinamento *dos requisitos funcionais* do sistema em desenvolvimento. A ferramenta da UML utilizada na modelagem de casos de uso é *diagrama de casos de uso.*

![](https://i.imgur.com/WyIuysc.png)

## Visão de Classe Participantes
A visão de classe participante(VCP), é um diagrama de classes onde seus objetos fazem parte de um caso de uso, dessa forma, é possível elaborar
um ou mais VCP's por cada caso de uso. Essa estratégia é usada para que não haja apenas um único diagrama de classe, que por conseguinte, resultaria em um diagrama muito extenso e complexo. Logo, como podemos ver a seguir, foram feitos vários VCP's a fim de facilitar a compreensão de cada um dos diagramas.
### Comprar produto
![](https://i.imgur.com/XWzRNsP.png)
### Lançar produto
![](https://i.imgur.com/ow78i5q.png)
### Realizar Cadastro
![](https://i.imgur.com/r8tIJeH.png)
### Realizar Devolução
![](https://i.imgur.com/4D8CWnb.png)
### Visualizar Rastreio
![](https://i.imgur.com/fn56zW0.png)

## Diagramas de sequência

A interação entre objetos para dar suporte a funcionalidade de um caso de uso denomina-se realização de um caso. A realização de um caso de uso descreve o comportamento de um ponto de vista interno ao sistem. O diagrama de sequência é um dos diagramas da UML que da suporte a essa modelagem, assim, o objetivo do diagrama de sequência é apresentar as interações entre objetos na ordem temporal em que elas acontecem.

### Lançar produto 2
![](https://i.imgur.com/ky28ILV.png)
### Realizar compra 2
![](https://i.imgur.com/0iOGbxi.png)
### Visualizar rastreio 2
![](https://i.imgur.com/dEeQft0.png)

## Diagramas de estado

A UML tem um conjunto rico de notações para desenhar um DTE. Alguns elementos básicos de um diagrama de transição de estados e as transições. Associados a estas últimas estão os conceitos de evento, ação e atividade. Diante disso, temos um diagrama de estados, onde um estado é uma situação na vida de um objeto durante a qual ele satifaz alguma condição ou realiza alguma atividade. O estado inicial é representado como um círculo preenchido e indica quando ele é criado. Só pode haver um estado inicial em um DTE. O estado final é representado como um círculo "eclipsado" e indica o fim do ciclo de vida de um objeto.

### Estados Pedido
![](https://i.imgur.com/oEnHVav.png)
### Estados Produto
![](https://i.imgur.com/pus7KYP.png)

## Diagramas de atividade

Um diagrama de atividade é um tipo especial de diagrama de estados, em que são representados os estados de uma atividade em vez dos estados de um objeto. Ao contrário dos diagramas de estados, que são orientados a eventos, diagramas de atividades são orientados a fluxos de controle. O diagrama de atividade pode ser visto como uma extensão dos fluxogramas. Além de possuir toda a semântica existente um fluxograma (com notação ligeiramente diferente), o diagrama de atividade possui notação para representar ações concorrente (paralelas), juntamente com a sua sincronização.

### Avaliar Produto
![](https://i.imgur.com/h4gGg7E.png)
### Realizar Compra 3
![](https://i.imgur.com/8sSrbtp.png)











