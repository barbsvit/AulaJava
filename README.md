# AulaJava
**Tipos de dados em Java** 

Tipos de dados são especificados de diferentes tamanhos e valores que podem ser armazenados na variável. Existem dois tipos de dados em java:

```
Tipo de dado primitivo: Incluem boolean, char, byte, short, int, long, float, e double.
Tipo de dado não primitivo: Incluem classes, interfaces e arrays.
```

Existem 8 tipos de dados primitivos em Java, que são:

```
Byte - Os bytes são dados primitivos que vão desde -128 até 127. Seu valor padrão é 0. Este tipo de dado é usado em mémorias de armazenamento de grandes matrizes pois ocupam menos espaço do que dados de tipo inteiro, podendo ser usado no lugar de tipos de dados "int". Sua sintaxe é: byte a = 10, byte b = -20.

Short - Short é um tipo de dado duas vezes menor do que o tipo inteiro. Ele varia entre os valores -32.768 e 32.767. Este tipo de dado pode ser utilizado no caso  de não necessitar um espaço tão grande de armazenamento. Exemplo: Registros de casas em um condomínio e registros de propriedades por pessoa. Sintaxe: short s = 10000, short r = -5000.

Int - Um dado de tipo int é um inteiro (também de tipo primitivo) usado para armazenamento de grandes espaços, como por exemplo certidões de óbito/nascimento por dia. Seu valor varia de -2.147.483.648 há 2.147.483.647. Sintaxe:  int a  = 100000, int b = -200000.

Long - Um tipo de dado long possui a alta quantidade de armazenamento, para casos em que o tipo int não suporta a quantidade inserida. É possível declarar e inicializar uma variável Long atribuindo a ela um literal decimal, hexadecimal, octal ou binário. Pode ter diferentes sintaxes, mas a principal seria: long a = 100000L, long b = -200000L.

Boolean - Dados boolean tratam de dados de verdadeiro ou falso, podendo-se atribuir a ele os valores de 0 e 1, ou on e off. Exemplo: Em uma checkbox é possível atribuir o valor true ou false para as condições a serem checadas. Casa a caixinha esteja preenchida será verdadeiro, caso não será falso. Sua sintaxe pode ser: boolean one = false.

Char - Char é um dado do tipo caracter, serve para armazenar um caractere (o char vem de character, que é caractere em inglês), e por essa função simples tem o tamanho do tipo short. Pode ser usado em em jogos por exemplo, com comandos simples como 'a' para pular e 'd' para ir para o lado. Esse tipo de dado é declarado entre aspas simples, sua sintaxe é: char letra A = 'A'.

Float - Float é um tipo de dado de ponto flutuante, tendo uma faixa de valores ilimitada. Este tipo de dado é mais utilizado para valores do tipo decimal, assim como o double. Seu valor padrão é 0.0f. Sintaxe:float f1 = 234.5f  

Double - Também é um tipo de dado ponto flutuante, que não deve ser usado para valores como moedas (real, dólar, euro). Seu valor padrão pe de 0.0d. O double ocupa 32 bits a mais que o Float. Sintaxe: double d1 = 12.3
```

**Estrutura Condicional em Java**

```
A estrutura condicional em java, assim como em C# e outras linguagens, possui a estrutura condicional do If/else, sendo normalmente usada para dados booleanos. 
```
***If e Else***

```
O if/else é uma estrutura de condição em que uma expressão booleana é analisada. Quando a condição que estiver dentro do if for verdadeira, ela é executada. Já o else é utilizado para definir o que é executado quando a condição analisada pelo if for falsa. Caso o if seja verdadeiro e, consequentemente executado, o else não é executado.

O if pode ser utilizado em conjunto com o else ou até mesmo sozinho, caso necessário.
Um pequeno exemplo disso seria:
```
```
public class Exemplo {
	
    public static void main(String[] args) {
        int resposta = 10;
        if (resposta == 10) {
            System.out.println(“Você acertou!”);
        } else {
            // Caso contrário, a frase abaixo será escrita
            System.out.println(“Você errou!”);
        }
    }
	
}
 ```
```
Também é possível encadear o if/else se necessário
```
***Switch Case***
```
A estrutura condicional switch/case é uma alternativa em caso de termos que utilizar diversos ifs no código. Múltiplos if/else encadeados podem tornar o código muito extenso, pouco legível e com baixo índice de manutenção.

O switch/case testa o valor contido em uma variável, realizando uma comparação com cada uma das opções. Cada uma dessas possíveis opções é delimitada pela instrução case.

Podemos ter quantos casos de análise forem necessários e, quando um dos valores corresponder ao da variável, o código do case correspondente será executado. Caso a variável não corresponda a nenhum dos casos testados, o último bloco será executado, chamado de default (padrão).
Um exemplo disso seria: 
```
```
public class Exemplo {
	
    public static void main(String[] args) {
        int mes = 2;
        switch (mes) {
            case 1:
                System.out.println(“O mês é janeiro”);
                break;
            case 2:
                System.out.println(“O mês é fevereiro”);
                break;
            default:
                System.out.println(“Mês inválido”);
                break;
            }
    }
}            
```
**Estrutura de repetição em Java**
```
Em linguagens de programação, loops são usados para executar uma sequencia de instruções / funções repetidamente quando algumas condições tornam-se true. Existem três tipos de loops em java. As principais estruturas de repetição na maioria das linguagens são o for e o while.
```
***For***
```
O for  é uma estrutura de repetição que executa uma instrução ou  um grupo de instruções zero ou mais vezes. O que muda entre as estruturas é a sintaxe, no caso do for a variável de controle, o valor inicial, o incremento e a condição de continuação do loop, são declarados como em uma espécie de cabeçalho, também chamado de cabeçalho da instrução for.
```
***While***
```
O while é uma estrutura de repetição, assim como o for a diferença entre eles é que no for temos a quantidade exata de quantas vezes o código será repetido, e o while usamos quando não sabemos quantas vezes o código será repetido para concluir a condição
```
***Do...While***
```
O Do...While é uma estrutura de repetição também, porém, ele é usado quando queremos repetir uma parte do código. Se o número de interações não é fixo, é recomendado usar o Do...While. 
```
Exemplos de sintaxe das estruturas de repetição:

```
For:
for (<variável de controle>, <análise da variável de controle>, <incremento da variável de controle>) {
    // Código a ser executado
}

While:
while (<condição>) {
    // Trecho de código a ser repetido
}

Do...While:
do{  
// código a ser executado  
} while (verdadeiro); 
```
**Tipos de Elementos Visuais no Android Studio**

• Views básicas:

• Pickers Views: 

• Views de listas: 

• Views para imagens: 

• Menus: 