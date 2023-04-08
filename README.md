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
O while é uma estrutura de repetição, assim como o for. A diferença entre eles é que no for temos a quantidade exata de quantas vezes o código será repetido, e o while usamos quando não sabemos quantas vezes o código será repetido para concluir a condição
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
```
Os tipos de elementos visuais tem haver com o que vai ser mostrado para o usuário em sua tela. Eles são divididos em oito classes, sendo elas: Text, Buttons, Widgets, Containers, Layout, Helpers, Google e Legacy e dentro de cada uma delas existem os tipos principais, isto é, aqueles de maior importância e/ou mais utilizados. 

Text: TextView (Visualização de texto para o usuário), AutocompleteTextView (Funciona como uma aba flutuante de correção e sugestão de texto), MultiAutocompleteTextView (Quase a mesma coisa que o anterior, porém, se trata de uma barra flutuante que sugere conclusões conforme se está digitando em um menu suspenso). 

Buttons: Button(Em tradução literal é um botão onde ao clicar realiza uma ação específica conforme o que foi solicitado. Exemplo: O botão de login de alguma rede), RadioButton(Funciona como um botão de múltipla opção, onde ao clicar em uma, essa ação não poderá ser desfeita, porém outra das três ou quatro opções poderá ser escolhida), Chips(É um elemento que representa uma entrada, atributo ou ação) e Switch (Um Switch é um widget de alternância de dois estados. Os usuários podem arrastar o botão "thumb" para frente e para trás para selecionar uma das duas opções ou simplesmente tocar no botão para alternar entre as opções).

Widgets: Cada um dos elementos da classe Widgets são diferentes entre si, possuindo apenas a semelhança na questão "View". Então é possível dizer que são elementos usados para questões diversas de importância do usuário. Ex: ImageView e VideoView. 

Containers: RecyclerView(O RecyclerView facilita a exibição eficiente de grandes conjuntos de dados. Você fornece os dados e define a aparência de cada item, e a biblioteca RecyclerView cria dinamicamente os elementos quando eles são necessários.Como o nome indica, RecyclerView recicla esses elementos individuais.), Spinner(É um comando de exibição de uma atualização de aprimoramento por vez.), FragmentContainerView(FragmentContainerView é um Layout personalizado projetado especificamente para Fragments. Ele estende FrameLayout, para que possa lidar com transações de fragmento de forma confiável.), ScrollView(Exibição de rolagem, exibindo mais de um por vez ).

Layout: ConstraintLayout(É um comando que define a posição de uma visualização, e é necessário uma restrição horizontal e uma vertical), LinearLayoutHorizontal(É um grupo de visualizadores que define a orientação de todos os "filhos" que pode ser Vertical ou Horizontal), FrameLayout(Ele foi criado para Bloquear uma área da tela para mostrar um único item).

Helpers: Group (Um grupo na tabela de slots. Representa uma chamada ou um nó emitido.), Barrier (Uma barreira faz referência a vários widgets como entrada e cria uma diretriz virtual com base no widget mais extremo no lado especificado.), Guideline(Linha de guia, como uma régua).

Google: MapView (é usado para mostrar uma localização). 

Legacy: ListView(Exibe uma coleção de exibições com rolagem vertical, onde cada exibição é posicionada imediatamente abaixo da exibição anterior na lista).
```

**REFÊRENCIAS**

https://developer.android.com/reference/kotlin/androidx/constraintlayout/core/widgets/Guideline?hl=en

https://blog.grancursosonline.com.br/os-tipos-primitivos-da-linguagem-java/

https://www.devmedia.com.br/tipos-de-dados-por-valor-e-por-referencia-em-java/25293

https://www.javatpoint.com/pt/tipo-de-dado-em-java

http://www.bosontreinamentos.com.br/java/tipos-de-dados-primitivos-em-java/

https://www.dca.fee.unicamp.br/cursos/EA876/apostila/HTML/node10.html#:~:text=Estrutura%20de%20dados%20%C3%A9%20o,a%20informa%C3%A7%C3%A3o%20manipulada%20pelo%20programa.

https://www.alura.com.br/artigos/estruturas-de-dados-introducao

https://www.freecodecamp.org/portuguese/news/as-principais-estruturas-de-dados-que-voce-deve-conhecer-para-sua-proxima-entrevista-de-programacao/

https://awari.com.br/estrutura-de-dados/?utm_source=blog

https://intranet.ifs.ifsuldeminas.edu.br/michelle.nery/Java%20-%20Subsequente/Aula%2015%20-%20Estruturas%20de%20Repeti%C3%A7%C3%A3o/Aula%2015%20-%20Estruturas%20de%20Repeti%C3%A7%C3%A3o.pdf



