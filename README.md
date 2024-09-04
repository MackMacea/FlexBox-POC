![flexbox](https://github.com/user-attachments/assets/7632f5b2-4e32-44e3-b301-04473bd85af6)
# Poc FlexBox
## O projeto a seguir tem por objetivo percorrer propriedades do FlexBox, mostrar seu funcionamento e seu código.



Conteudos deste projeto
------------------------
<!--ts-->
* [Flex Container](#Flex-Container) <br>
    * [Flex-Direction](#Flex-Direction) <br>
    * [Flex-Wrap](#Flex-Wrap)  <br>
    * [Flex-Flow](#Flex-Flow) <br>
    * [Justify-Content](#Justify-Content)<br>
    * [Align-Items](#Align-Items) <br>
    * [Align-Content](#Align-Content) <br>
    * [Centralizar perfeitamente](#Centralizar-perfeitamente) <br>
* [Flex Items](#Flex-Items) <br>
    * [Child Elements](#Child-Elements)<br>
    * [Order Property](#Order-Property)<br>
    * [Flex-Grow](#Flex-Grow)<br>
    * [Flex-Shrink](#Flex-Shrink)<br>
    * [Flex-Basis](#Flex-Basis)<br>
    * [Flex-Property](#Flex-Property)<br>
    * [Align-Self](#Align-Self)<br>
* [Flex Responsive](#Flex-Responsive)<br>
    * [Responsive-Flexbox](#Responsive-Flexbox)<br>
    * [Responsive-Image](#Responsive-Image)<br>
    * [Responsive-Website](#Responsive-Website)
  <!--te-->



## Flex Container

Para a demonstração visual das propriedades do Flex Container utilizaremos o seguinte layout HTML/CSS
<div width=100% display:flex>
<img width=45% src="./images/Codigo HTML utilizado.png">
<img width=45% src="./images/apenas flex css.png">
</div>

### Flex-Direction
Define a direção em que o container vai organizar os itens

### Column
Organiza verticalmete
<img src="./images/flex direction column.png">

### Column-Reverse
Organiza verticalmente (mas do final até o começo)
<img src="./images/column reverse.png">

### Row
Organiza horizontalmente
<img src="./images/row.png">


### Row-Reverse
Organiza horizontalmente (mas do ultimo até o primeiro)
<img src="./images/row reverse.png">

## Flex-Wrap
Define se os itens devem ser encapsulados ou não

Aqui utilizaremos um outro modelo HTML para melhor exemplificação.
<img src="./images/Flex wrap html.png">

### Flex-Wrap
Encapsula os itens
<img src="./images/flex wrap.png">

### No Wrap
Não encapsula os itens 
<img src="./images/no wrap.png">

### Wrap reverse
Encapsula os intens na ordem reversa
<img src="./images/wrap reverse.png">

## Flex-Flow
Esta propriedade é uma junção das propriedades Wrap e Row, por conta disso todas as propriedades anteriores podem ser aplicadas do seguinte modo

### Exemplo 1
Aqui utilizamos row e wrap para organizar os itens
<img  src="./images/flex flow base css.png">
<img  src="./images/flex flow base.png">


### Exemplo 2
Aqui trocamos o row pelo row reverse para organizar os itens
<img src="./images/flexflow row reverse.png">
<img src="./images/flex flow row reverse.png">


## Justify-Content
Utilizada para alinhar itens


### Center
Alinha no centro
<img src="./images/justify content center.png">

### Flex Start
Alinha ao começo do container
<img src="./images/justify lfex start.png">

### Flex End
Alinha ao final do container
<img src="./images/Justify Flex end.png">

### Space Around
Alinha com um espaço maximo entre os itens.
<img src="./images/space around.png">

### Space Between
Alinha com o espaço maximo entre os itens
<img src="./images/Space Between.png">

### Space Evenly
Alinah com o mesmo espaço antes, entre e depois dos itens
<img src="./images/space evenly.png">

## Align-Items
Alinha os itens em relação ao espaço em relação ao container

### Center
Alinha ao centro
<img src="./images/align item center.png">

### Flex Start
Alinha na parte superior do container
<img src="./images/aligm item flex startt.png">

### Flex End
Alinha na parte inferior do container
<img src="./images/align item flex end.png">

### Stretch
Alinha sobre o espaço do container
<img src="./images/alignn item strech.png">

### Baseline
Alinha os itens a faixa central do container com a faixa central da div filha

Aqui modificamos os tamanhos das Div Filhas e o tamanho de fonte usado em cada uma para melhor demonstração
<img src="./images/align item baseline.png">

## Align-Content
Alinha o conteudo inteiro em relação ao espaço do container

Aqui modificamos o tamanho do container e a quantidade de divs filahs para a melhor demonstração

### Space Between
Alinha com um espaço entre as linhas
<img src="./images/align content space between.png">

### Space Around
Alinha com um espaço antes, entre e depois das linhas
<img src="images/align item space around.png">

### Stretch
Alinha as linhas fazendo-as ocupar o espaço restante do container
<img src="./images/align item strch.png">

### Center
Alinha as linhas no centro do container
<img src="./images/align content center.png">

### Flex Start
Alinha no inicio do container
<img src="./images/align content flex startt.png">

### Flex End
Alinha no final do container
<img src="./images/Align content flex end.png">

## Centralizar perfeitamente
Podemos centralizar algo perfeitamente utilizando o Justify-Content:Center e o Align-Items:Center, como mostra o exemplo a seguir

![image](https://github.com/user-attachments/assets/ad7142db-eba9-442c-b7bb-e0952ae69e76)
<img src="./images/centro perfeito.png">

## Child Elements
Os elementos filhos diretos de um contêiner flexível se tornam automaticamente itens flexíveis (flex). As propriedades do Flex Item são: Order, Flex-grow, Flex-shrink, Flex-basis, Flex e Align-self.

<img src="./images/Child Elements.jpeg">

O elemento acima representa quatro itens flexíveis verdes claro dentro de um contêiner flexível verde.

### The Order Property
A propriedade Order especifica a ordem dos itens flexíveis.

<img src="./images/Order Property.jpeg">

O primeiro item flexível no código não precisa aparecer como o primeiro item no layout.
O valor do pedido deve ser um número, o valor padrão é 0.

Exemplo:

<img src="./images/Order Property HTML.jpeg">

### Flex-Grow
A propriedade  flex-grow especifica o quanto um item flexível crescerá em relação ao restante dos itens flexíveis.

<img src="./images/Flex Grow.jpeg">

O valor deve ser um número, o valor padrão é 0.

<img src="./images/FLex Grow HTML.jpeg">

### Flex-Shrink
A propriedade flex-shrink especifica o quanto um item flexível encolherá em relação ao restante dos itens flexíveis.
O valor deve ser um número, o valor padrão é 1.

<img src="./images/Flex Shrink.jpeg">

<img src="./images/Flex Shrik HTML.jpeg">
<img src="./images/Flex Shrink HTML 2.jpeg">

### Flex Basis
A propriedade flex-basis especifica o comprimento inicial de um item flexível.

<img src="./images/Flex Basis.jpeg">
<img src="./images/Flex Basis HTML.jpeg">

### Flex Property
A flex property é uma abreviação para as propriedades flex-grow, flex-shrinke flex-basis.

<img src="./images/Flex Property.jpeg">
<img src="./images/Flex Property HTML.jpeg">

### Align-Self
A propriedade align-self especifica o alinhamento do item selecionado dentro do contêiner flexível.

A propriedade substitui o alinhamento padrão definido pela propriedade align-self do contêiner .align-items

Nestes exemplos usamos um contêiner de 200 pixels de altura, para demonstrar melhor a propriedade align-self:

<img src="./images/Align Self.jpeg">
<img src="./images/Align Self 2.jpeg">
<img src="./images/Align Self HTML.jpeg">
<img src="./images/Align Self HTML 2.jpeg">

## Responsive Flexbox
É possível usar media queries para criar layouts diferentes para diferentes tamanhos de tela e dispositivos.

Por exemplo, se você quiser criar um layout de duas colunas para a maioria dos tamanhos de tela e um layout de uma coluna para telas pequenas (como celulares e tablets), você pode alterar o flex-direction de row para column em um ponto de interrupção específico (800px no exemplo abaixo):

<img src="./images/
