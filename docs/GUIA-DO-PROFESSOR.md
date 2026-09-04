# Guia do professor — Missão Kits da Festa

## Antes de começar

O jogo apresenta o MDC como uma decisão de organização: usar todo o estoque para montar o maior número possível de kits iguais. Não anuncie a sigla no início. Convide a turma a resolver o problema da festa.

O progresso é armazenado somente no navegador. Não é necessário instalar programas, criar conta ou informar dados pessoais.

## Objetivos de aprendizagem

Espera-se que o estudante consiga:

- reconhecer quando uma quantidade divide três números sem resto;
- interpretar itens por kit e itens que sobram;
- explicar por que uma quantidade válida pode não ser a maior;
- relacionar a montagem dos kits à divisão;
- usar a expressão `MDC(a, b, c)` depois de compreender a situação.

## Roteiro sugerido de 50 minutos

| Tempo | Atividade |
| --- | --- |
| 5 min | Apresente a festa: todos os kits precisam ser iguais e nenhum item pode sobrar. |
| 10 min | Teste coletivamente uma quantidade que deixe sobra. Pergunte o que essa sobra informa. |
| 20 min | Estudantes resolvem duas ou três missões em dupla ou individualmente. |
| 10 min | Compare estratégias: testar divisores, começar por valores maiores e usar divisão. |
| 5 min | Formalize a descoberta com a expressão MDC e proponha um novo estoque. |

## Perguntas para mediação

- “Todos os kits receberam a mesma quantidade?”
- “Qual item ficou no estoque?”
- “Essa quantidade funciona para maçãs, biscoitos e adesivos?”
- “Se nada sobrou, conseguimos atender ainda mais crianças?”
- “Como uma divisão confirma sua resposta?”

Evite revelar o MDC. Quando uma tentativa funcionar, valorize a descoberta e devolva a pergunta: “É possível montar mais kits?”.

## Exemplo coletivo

Considere 12 maçãs, 18 biscoitos e 30 adesivos:

- 4 kits: cada kit recebe 3 maçãs, 4 biscoitos e 7 adesivos; sobram 2 biscoitos e 2 adesivos;
- 6 kits: cada kit recebe 2 maçãs, 3 biscoitos e 5 adesivos; nada sobra;
- mais de 6 kits: nenhuma quantidade maior divide exatamente os três estoques.

Depois da investigação, registre:

```text
12 ÷ 6 = 2 maçãs por kit
18 ÷ 6 = 3 biscoitos por kit
30 ÷ 6 = 5 adesivos por kit
MDC(12, 18, 30) = 6
```

## Laboratório de kits

No laboratório, escolha estoques de 2 a 1.000 itens. Para valores altos, incentive a entrada direta do número de kits e a verificação por divisão.

A escala visual muda automaticamente acima de 100, mas a resposta abaixo de cada item sempre informa:

- quantos kits foram montados;
- quanto cada kit recebe;
- quantos itens ficam no estoque.

Desafios úteis:

| Estoque | MDC | Questão de aprofundamento |
| --- | ---: | --- |
| 120, 180, 300 | 60 | Por que 30 kits funcionam, mas não são o máximo? |
| 240, 360, 600 | 120 | Quanto de cada item entra em um kit? |
| 375, 500, 625 | 125 | Como verificar sem testar todos os números? |
| 384, 576, 960 | 192 | Que divisões confirmam a solução? |

## Estoque surpresa

Use o modo surpresa para prática depois que a turma compreender “kits iguais, sem sobra e o maior número possível”. O gerador oferece limites de 60, 100, 300 e 1.000, além da opção de incluir desafios com MDC igual a 1.

Quando o MDC é 1, apenas um kit consegue usar todo o estoque igualmente. Esse caso ajuda a mostrar que nem sempre é possível atender várias crianças com kits idênticos usando todos os itens.

## Registro de aprendizagem

Uma justificativa pode seguir este modelo:

```text
Tentei montar ____ kits.
Cada kit receberia ____________________.
Sobraram ____________________.
Depois, testei ____ kits e nada sobrou.
Esse é o maior número possível porque ____________________.
Logo, MDC(____, ____, ____) = ____.
```

## Configurações e privacidade

O painel do professor permite ativar ou desativar dicas, pontos e a linguagem formal. O botão de reiniciar progresso apaga apenas as informações guardadas localmente no navegador. Nenhum dado é enviado a servidores.
