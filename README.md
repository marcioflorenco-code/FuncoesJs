# FuncoesJs
atividade tutorial sobre funcoes (declaration,expression,arrow)

as funçoes em javascript podem ser feita com tres metodos diferentes , sendo eles : DECLARATION , EXPRESSION , ARROW , elas entre si tendem a ter semelhanças porem com caracteristicas diferentes , ambas com um sentido parecido ja que sao funçoes , a seguir vamos analisar como cada uma delas construidas e seu formato de uso.

primeiro vamos falar sobre !
**DECLARATION FUNCTION**

nela nos vamos declarar a funçao ,e dentro dela vamos colocar qual açao sera realizada, de forma mais direta como vou mostra no exemplo abaixo :
```js
function somar(A,B){
    return A+B;
}
somar(1,5);
```

como podemos ver na funçao acima , o comando de soma sera realizado no **return** onde eu atribui que os valores de A e B que irão ser somados, e acima na funçao coloquei os parametros para que recebessem o valor de A e B para assim ser realizado a soma, o **somar** sera o identificador dela para receber os valores como colocado abaixo sendo A=1 e B=5.


agora vamos analisar a funçao !
**EXPRESSION FUNCTION**

agora diferente do **declaration function** nela podemos usar um LET para colocar a funcao, colocando para que tipo de operacao sera realizada como no exemplo a seguir !

```js
let somar = function(A,B){
    return A+B
}
somar(5,7);
```

nela podemos perceber que haverar a adicao do LET que vai servir para identificar o tipo de operacao realizada de forma mais completa, onde dentro dela a funçao ira ser realizada , a açao usada foi a de soma representado por A+B, podendo tambem ter outro tipo de opeçao, uma observaçao a ser analisada e que se for usado um console para realizar a açao da operaçao acima o LET tera que ser usado antes do console pois sendo colocado apos o console nao havera a leitura da funçao , porem ha uma maneira de simplificar esse tipo de açao , usando a funçao que sera apresentada a seguir!

por fim vamos analizar a funçao !
**ARROW FUNCTION**

agora essa funçao tende a ter como objetividade simplitificar o que foi mostrado no **expression function** dando uma enfase maior na operaçao a ser realizada 

```js
let somar = (A,B) => A+B ; 
let subtrair = (A,B) => A-B;

let calcular = (A,B,operaçao) =>{
     return operaçao(A,B);
}
calcular (1,4,subtrair);

```
usando essa forma a operaçao sera realizada assim como mostrado no **expression function** porem de forma resumida , nesse exemplo o usuario poderia escolher qual tipo de operacao ele vai executar , no exemplo o usuario pediu para subtrair , logo ele ira prucurar a funçao de subtrair e ira executa-la , pois antes nos atribuimos as operaçoes de soma e subtrair na funçao dando uma maior volatividade ao usuario de escolher a operaçao de sua preferencia.

porem sem precisar que o usuario peça, ele mesmo assim executa a operaçao como no exemplo abaixo !

```js
let somar = (A,B) => A+B ;

somar(1,5);
```
como podemos ver a funçao ja foi aplicada diretamente , e os valores atribuidos ela irao executar da mesma maneira que mostrado no exemplo anterior , apenas mudando que a operaçao sera feita de maneira pratica para açoes mais simples como mostrado , sem a necessidade de escolha por parte do usuario !

