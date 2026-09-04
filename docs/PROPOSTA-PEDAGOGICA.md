# Proposta pedagógica — Missão Kits da Festa

## Finalidade

**Missão Kits da Festa** apresenta o Máximo Divisor Comum a crianças, preferencialmente entre 8 e 12 anos, por meio de uma situação próxima: preparar kits iguais para uma festa escolar.

Há três tipos de item no estoque — maçãs, biscoitos e adesivos — e todos devem ser distribuídos. A criança procura o maior número de kits idênticos que pode montar sem deixar nada sobrando.

O objetivo é perceber que:

1. uma quantidade de kits só funciona quando divide exatamente todos os estoques;
2. várias quantidades podem funcionar;
3. quanto mais kits válidos, mais crianças recebem materiais iguais;
4. o maior número que funciona recebe o nome de Máximo Divisor Comum.

## Princípio de aprendizagem

O jogo segue a sequência:

> experimentar → observar → testar → errar → comparar → descobrir → nomear → calcular

A sigla MDC não é o ponto de partida. Primeiro, a criança observa o efeito de suas decisões. Uma sobra é informação útil para a próxima tentativa, não uma punição.

## Mecânica

Para cada missão, a criança:

1. confere as quantidades de maçãs, biscoitos e adesivos;
2. escolhe quantos kits iguais deseja montar;
3. vê quanto de cada item entraria em cada kit;
4. identifica visualmente os itens que sobrariam;
5. quando nada sobra, investiga se consegue montar mais kits;
6. confirma o maior número possível;
7. relaciona sua descoberta à notação `MDC(a, b, c) = g`.

Exemplo: com 12 maçãs, 18 biscoitos e 30 adesivos, quatro kits deixam dois biscoitos e dois adesivos no estoque. Seis kits recebem 2 maçãs, 3 biscoitos e 5 adesivos cada, sem sobra. Portanto, `MDC(12, 18, 30) = 6`.

## Progressão

| Etapa | Pergunta principal | Apoio |
| --- | --- | --- |
| 1. Primeiros kits | “Todos receberam a mesma quantidade?” | Itens, cartões de kit e sobra destacados |
| 2. Comparação | “Essa quantidade funciona para os três estoques?” | Registro das tentativas |
| 3. Maior quantidade | “Podemos atender mais crianças?” | Confirmação separada do resultado |
| 4. Formalização | “Que cálculo explica a montagem?” | Divisão, divisores comuns e notação MDC |

## Estoques de até 1.000 itens

O laboratório aceita três números inteiros de 2 a 1.000. A criança pode digitar diretamente o número de kits ou usar controles de `−1`, `+1`, `−10` e `+10`.

- **Até 100 itens:** cada unidade aparece como uma marca no estoque.
- **De 101 a 1.000:** os três estoques usam uma escala comum com no máximo 100 marcas por item.

Em qualquer escala, os cartões informam a distribuição exata: quantidade de kits, itens por kit e sobra. A compactação visual não altera nem esconde o resultado matemático.

## Modo surpresa

O gerador começa por um MDC-alvo `g` e multiplica esse valor por três números cujo MDC é 1. Assim, o resultado real é conhecido internamente sem ser revelado à criança.

O modo evita estoques repetidos e permite limites de 60, 100, 300 ou 1.000. Por padrão, o MDC é maior que 1. O caso `MDC = 1` pode ser incluído como desafio avançado.

## Avaliação formativa

Evidências de aprendizagem incluem:

- verificar os três estoques antes de confirmar;
- explicar por que determinada quantidade deixou sobra;
- diferenciar “funciona” de “é o maior número que funciona”;
- justificar a solução usando divisão ou divisores;
- transferir a estratégia para um estoque maior.

Estrelas e pontos registram o percurso, mas não devem substituir a observação das estratégias utilizadas.

## Acessibilidade

A informação essencial aparece em texto, símbolos e formas, sem depender apenas de cores. Os controles são grandes, aceitam teclado e se adaptam a telas pequenas. Animações e elementos festivos apoiam a compreensão sem competir com os estoques, kits e sobras.
