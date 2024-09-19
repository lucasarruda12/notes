# Sentenças atômicas

- A FOL é formada por uma família de linguagens, que tem grmáticas similares,memos conectivos e quantificadores, diferem novocbulário parausar as sentenças maiis básicas (sentenças atômicas).
.
- Sentenças atômicas são as sentenças mais simples.

## Nomes e predicados

- Versões diferentes têm nomes e predicados diferentes.

### Taskis World

- Nomes: b, e, n...
- Predicados: Cube, Larger, Between
- sentenças atômicas:
    - Cube(b)
    - Larger(c, f)
    - Between(b, c, c)

### Outras versões

- Teoria dos conjuntos
- Aritimética

## Contantes individuais

- Simbolos usados para se referir a um objeto fixo individualmente
    - max representa o Indivíduo Max
    - 1 representa o número "um"

## Taskis World

- a até f e n1, n2...

### Diferenças para o mundo real

- Nomes se referem a exatamente Um objeto
- Nomes devvem se referir a algum objeto
- Um objeto pode ter nomes diferentes
- Um objeto pode não ter nome

## Nomes em FOL

- Toda constante deve dar nome a um objeto
- Nenhuma constante pode dar nome a mais de um objeto

## Simbolos de predicado

- Usado para expressaralgumaprorpiedade dos objetosou relação entre eles.
- Combinamos nomes e predicados para formar sentenças atômicas.
- Não são exatamente os predicados da gramática.

````
[A]     gosta de    [B]
----    --------    ----
Nome    Predicado   Nome
````

- Em FOL, o número de argumentos é fixo (aridade).

## Predicados no mundo de Tarski

- Não anotei não. Crie vergonha na cara e vá pesquisar no Google.

## Propriedades determinadas

- Em português, algumas proppriedades não são claras..
    - "Clara é jovem" (Até quantos anos uma pessoa é jovem?).

- Em FOL, ppropriedades determinadas possuem um fato definitivo que determinam se um objeto possui aquela propriedade ou não.

- Todo predicado tem um significado bem determinado e uma aridade fixa.

## Sentenças Atômicas

- Sentença formada por um predicado seguido pelo numero correto de nomes
- Notação infixa vs prefixa
- Ordem dos nomes em uma sentença atômica é importante
    -  "pipipi > popopo" /= "popopo > pipipi"

## Reinvidicações

- Sentenças são reinvindicações (algo que é verdadeiro o falso)
- Toda sentença atômica é verdadeira ou falsa

## Linguagem de primeira ordem

- Diferenciam-se pelosnomes e predicados usado spara formar as sentenças atômicas
- Compartlham s mesmos conectivos e quantificadores
- Tradução

## Projetando linguagens

- Que nomes e predicados você precisa
    - Projetado sob demanda

- Diversas maneiras de traduzir
- Clara deu ma camisa a max
- Deu(camisa, clara, max)

## Objetos

- Nomes podem ser introduzidos em ma FOL para identificar qalquer oisa que possa ser considerada um objeto

- Objeto é qualquer coisa sobre o qual possamos fazer asserções

## Regra geral

- Defina uma linguagem que defina o que você precisa com o mínimo de predicados possível

## Termo

- Sentenças que intuitivamente referenciam aum indivíduo são termos
    - omportam-se como constantes individuais
    - Constantes individuais sãos os termos mais simlpes- Termos mais complexos são construídos usando constantes individuais e símbolos de funções

## Termos complexos

- Em FOL "O pai de Max" se torna pai(max)

## Simbolos de função vs predicados

- Ambos recebem termos como parâmetros
- Função + termo retorna um termo
- Predicado + termo retorna um valor verdade
- Predicados são indicados por letras maiúsculas
- Funções seráo iniciados por letras minúsculas

## Simbolos de função

- Devem referenciar exatamente um objeto
- Suposição artificial, pois na linguagem natural isso nem sempre é verdade
- Termos complexos são fomrados por um símbolo de funçao de aridade n com n termos aplicados

## Funções no Mundo de Tarski

- Não existem

## Notação alternativa

- Existem diferentes notações para uma mesma FOL