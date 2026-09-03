# Guia do professor — Oficina das Fitas

## Antes de começar

Abra o jogo em um navegador moderno. Não é necessário criar conta nem instalar programas. O progresso fica salvo apenas no navegador e dispositivo em uso; se a turma compartilhar computadores, oriente cada estudante a usar uma sessão ou combine quando o progresso deve ser reiniciado.

O jogo apresenta o MDC como um problema de repartição: três fitas precisam ser cortadas em pedaços iguais, sem sobras e no maior comprimento possível. O foco inicial é o raciocínio, não a memorização da sigla.

## Objetivos de aprendizagem

Ao final da atividade, espera-se que o estudante consiga:

- reconhecer se um número divide três comprimentos sem deixar resto;
- interpretar grupos completos e sobras;
- explicar por que um divisor comum pode não ser o maior divisor comum;
- usar a expressão `MDC(a, b, c)` após a descoberta do conceito;
- verificar a resposta por divisões exatas ou por divisores comuns.

## Roteiro de aula de 50 minutos

| Tempo | Proposta |
| --- | --- |
| 5 min | Apresente a missão: cortar três fitas no maior tamanho igual possível, sem sobrar. Não anuncie ainda a sigla MDC. |
| 10 min | Resolva coletivamente uma carta inicial. Pergunte o que a sobra informa e se um tamanho que funciona pode ser superado. |
| 20 min | Estudantes jogam duas ou três cartas da trilha, em duplas ou individualmente. Peça que registrem ao menos uma tentativa que deixou sobra. |
| 10 min | Socialize estratégias: testar divisores, começar por valores altos, usar divisões e comparar resultados. Introduza a notação MDC. |
| 5 min | Proponha um desafio de saída: criar ou resolver um conjunto novo e justificar o maior tamanho. |

## Uso da trilha

As dez cartas foram organizadas do suporte visual mais concreto para desafios em que a estratégia importa mais que os blocos. As cartas podem ser revisitadas livremente; não é necessário bloquear estudantes que desejam retomar uma fase anterior.

Durante as primeiras cartas, privilegie perguntas como:

- “Onde a fita deixou sobra?”
- “Esse tamanho funcionou em todas ou apenas em uma delas?”
- “Como sabemos que não existe um pedaço maior?”

Depois que a turma encontrar um maior tamanho comum, formalize a descoberta com a divisão. Por exemplo, se as fitas têm 12, 18 e 30 unidades e o maior pedaço é 6, registre `12 ÷ 6 = 2`, `18 ÷ 6 = 3` e `30 ÷ 6 = 5`; então apresente `MDC(12, 18, 30) = 6`.

## Laboratório: desafios criados pela turma

No laboratório, informe três inteiros de **2 a 1.000**. Para valores altos, prefira que estudantes digitem o tamanho de pedaço que desejam testar em vez de depender exclusivamente dos botões de aumentar e diminuir. A visualização se adapta automaticamente:

- de 2 a 100, cada unidade pode aparecer como bloco;
- de 101 a 1.000, a fita vira uma escala comum com no máximo 100 marcas, cortes, grupos e sobra identificados;
- o painel textual informa sempre quantos grupos completos foram formados e qual foi a sobra.

Peça que a turma crie desafios para outra dupla. Antes de entregar o desafio, quem o criou deve registrar o MDC e uma justificativa, para conseguir conferir a solução sem revelar a resposta de início.

Exemplos para discussão:

| Fitas | MDC | Pergunta de aprofundamento |
| --- | ---: | --- |
| 120, 180, 300 | 60 | Por que 30 funciona, mas não é a resposta final? |
| 240, 360, 600 | 120 | Como confirmar a resposta usando divisões? |
| 375, 500, 625 | 125 | O que as três fitas têm em comum? |
| 384, 576, 960 | 192 | Que estratégia evita testar todos os números? |

## Modo aleatório

Use o botão de desafio aleatório para oferecer prática adicional ou formar estações de aprendizagem. O modo gera três valores entre 2 e 1.000 com um MDC calculado internamente; a resposta não deve ser mostrada antes da confirmação do estudante.

Sugestões de mediação:

- Gere um desafio para toda a turma e recolha hipóteses diferentes antes de testar.
- Peça que uma dupla explique por que um divisor comum menor não encerra a busca.
- Compare dois desafios aleatórios: um com MDC alto e outro com MDC igual a 1, quando esse caso for habilitado.
- Para apoio, mantenha as dicas e a linguagem formal ativadas; para desafio, reduza a ajuda visual somente depois que a estratégia estiver consolidada.

O modo aleatório não é indicado como primeiro contato isolado. A trilha inicial oferece exemplos cuidadosamente graduados; use a aleatoriedade depois que a turma compreender a regra de “sem sobra e o maior possível”.

## Acompanhamento e feedback

Observe o percurso, não somente o número final. Uma justificativa oral ou escrita pode usar uma destas estruturas:

```text
Testei ____. Ele não funcionou porque a fita ____ deixou sobra de ____.
Testei ____. Ele divide as três fitas sem sobra.
Ele é o maior porque ____.
Portanto, MDC(____, ____, ____) = ____.
```

As estrelas, pontos e uso de dicas podem motivar, mas não devem penalizar quem investiga mais. Uma criança que testa valores de modo sistemático pode demonstrar compreensão profunda mesmo com mais tentativas.

## Configurações e privacidade

O painel de configurações permite adequar dicas, pontuação e a apresentação da linguagem formal. Se a atividade for diagnóstica, considere ocultar a pontuação e registrar as estratégias observadas. Ao fim de uma turma compartilhando o mesmo equipamento, o botão de reiniciar progresso limpa os dados locais.

Não há coleta nem envio de dados. Evite solicitar que estudantes escrevam nomes completos no jogo; para uma atividade avaliativa, use uma folha, ambiente institucional ou outro procedimento autorizado pela escola.
