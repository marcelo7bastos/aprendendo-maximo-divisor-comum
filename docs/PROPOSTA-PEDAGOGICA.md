# Proposta pedagógica — Oficina das Fitas

## Finalidade

**Oficina das Fitas** é um recurso digital para introduzir o Máximo Divisor Comum (MDC) a estudantes, preferencialmente entre 8 e 12 anos, sem partir de regra, algoritmo ou notação formal. A atividade apresenta três fitas com comprimentos distintos e propõe uma tarefa concreta: preparar pedaços do mesmo tamanho, sem desperdício, usando o maior pedaço possível.

O objetivo matemático é que o estudante reconheça que:

1. um tamanho só serve quando divide todos os comprimentos sem resto;
2. vários tamanhos podem servir ao mesmo tempo;
3. o problema pede o maior entre os tamanhos comuns;
4. essa ideia recebe o nome de Máximo Divisor Comum.

## Princípio de aprendizagem

O jogo organiza a descoberta nesta sequência:

> experimentar → observar → testar → errar → comparar → descobrir → nomear → calcular

Isso evita que a sigla MDC apareça como uma resposta a memorizar antes que a criança compreenda a necessidade que ela resolve. A tentativa que deixa sobra é uma evidência visual útil: não é tratada como erro punitivo, mas como informação para orientar o próximo teste.

## Narrativa e mecânica

O estudante atua como **Mestre das Medidas** de uma oficina. Para cada missão:

1. observa os comprimentos das três fitas;
2. escolhe um tamanho de pedaço;
3. testa o corte e vê grupos completos e eventuais sobras;
4. quando encontra um divisor comum, investiga se há outro maior;
5. confirma sua hipótese;
6. só então recebe a explicação formal: `MDC(a, b, c) = g`.

O retorno visual deve ser acompanhado de linguagem simples. Por exemplo: “18 deixa sobra de 2 unidades” e uma região final destacada na fita. Quando o tamanho funciona, o jogo não encerra imediatamente; pergunta se ainda pode existir um pedaço maior.

## Progressão sugerida

| Etapa | Foco | Apoio oferecido |
| --- | --- | --- |
| 1. Descoberta visual | Agrupar fitas e reconhecer sobra | Blocos e mensagens concretas; sem sigla MDC |
| 2. Descobrindo padrões | Relacionar grupos, divisão e resto | Resultado de cada teste e comparação entre tentativas |
| 3. Conhecendo o MDC | Nomear o maior divisor comum | Notação MDC, divisores comuns e divisões exatas |
| 4. Pensando sem os blocos | Generalizar o raciocínio | Visualização sob demanda e maior autonomia |

A trilha inicial contém dez cartas de dificuldade gradual. Ela funciona como porta de entrada; a criança pode revisitar cartas anteriores para consolidar estratégias.

## Laboratório e números até 1.000

O laboratório permite informar três números inteiros entre **2 e 1.000**. Esse intervalo amplia a investigação sem exigir que a pessoa avance pelo seletor uma unidade por vez. Para o tamanho do pedaço, a interface deve oferecer entrada numérica direta, controles de `−1`, `+1`, `−10` e `+10`, além do teclado. O valor válido do corte vai de 1 até o menor comprimento das três fitas.

O limite de 1.000 pede uma representação diferente da usada com valores pequenos. Desenhar mil blocos individuais cria rolagem excessiva, atrapalha a comparação e não acrescenta compreensão. A visualização adaptativa preserva o significado matemático assim:

- **De 2 a 100:** blocos unitários, com a última unidade de cada grupo marcada.
- **De 101 a 1.000:** fita em escala comum com, no máximo, 100 marcas por fita, indicação compacta dos grupos completos e uma sobra colorida proporcionalmente separada.

Em todos os níveis de visualização, o texto deve declarar a operação, por exemplo: `840 = 7 grupos de 120` ou `845 = 7 grupos de 120 e sobra 5`. A compactação nunca pode esconder uma sobra nem alterar o resultado do teste.

## Modo aleatório

O modo aleatório serve para prática, recuperação e ampliação, sem substituir a sequência guiada. Um conjunto aleatório pedagogicamente adequado deve:

1. escolher um MDC-alvo `g` compatível com o intervalo de 2 a 1.000;
2. gerar multiplicadores positivos `p`, `q` e `r` cuja combinação tenha MDC igual a 1;
3. criar os comprimentos `g×p`, `g×q` e `g×r`;
4. descartar resultados repetidos, triviais ou superiores a 1.000;
5. variar a dificuldade pelo tamanho do MDC, pelos multiplicadores e pelo grau de apoio visual.

Esse procedimento garante que o MDC do desafio seja exatamente `g`, sem expor a resposta ao estudante. O gerador deve evitar que os três números sejam iguais e deve preferir desafios com MDC maior que 1, exceto quando a intenção for trabalhar o caso especial `MDC = 1`.

## Avaliação formativa

O professor pode observar evidências em vez de apenas a resposta final:

- a criança verifica todas as fitas antes de concluir;
- interpreta corretamente a sobra;
- diferencia “funciona” de “é o maior que funciona”;
- justifica uma tentativa com divisão, grupos ou lista de divisores;
- transfere a estratégia para um desafio sem blocos.

Estrelas, tentativas e dicas são indicadores de percurso. Não devem ser usados isoladamente para atribuir nota, porque explorar alternativas faz parte da aprendizagem pretendida.

## Inclusão e acessibilidade

O jogo deve manter texto explícito junto às cores e ícones, oferecer contraste suficiente, controles grandes e operação por teclado. A informação essencial não pode depender somente de animação, cor ou quantidade de blocos. Para telas pequenas e números altos, a fita em escala e as operações escritas são essenciais para preservar a legibilidade.
