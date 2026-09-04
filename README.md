# Missão Kits da Festa — Aprendendo MDC

Um jogo educativo, visual e responsivo para crianças descobrirem o **Máximo Divisor Comum (MDC)** enquanto organizam kits iguais para uma festa escolar.

Em vez de começar por uma fórmula, o jogo propõe uma pergunta concreta:

> Qual é o maior número de kits iguais que podemos montar sem deixar nenhum item sobrando?

A aprendizagem segue o percurso:

> experimentar → observar → testar → comparar → descobrir → nomear → calcular

## Como jogar

Abra [index.html](index.html) no navegador ou acesse a versão publicada no [GitHub Pages](https://marcelo7bastos.github.io/aprendendo-maximo-divisor-comum/).

Em cada missão há um estoque de maçãs, biscoitos e adesivos. A criança escolhe quantos kits quer montar. O jogo mostra:

- quantos itens de cada tipo entram em cada kit;
- quais itens ficam no estoque quando a divisão não é exata;
- se ainda é possível montar mais kits iguais.

A expressão `MDC(a, b, c)` aparece somente depois que a criança encontra o maior número de kits possível.

## Modos disponíveis

- **Trilha de missões:** dez desafios com dificuldade gradual.
- **Estoque personalizado:** escolha três quantidades entre 2 e 1.000.
- **Estoque surpresa:** gere conjuntos aleatórios com MDC conhecido.
- **Desafio MDC = 1:** opção avançada no gerador aleatório.
- **Área do professor:** controle dicas, pontuação e apresentação da linguagem formal.

No modo aleatório, é possível escolher limites de 60, 100, 300 ou 1.000 itens.

## Como o estoque aparece na tela

O tabuleiro é um caderno quadriculado: **cada linha é um kit**. A divisão vira um retângulo de marcas e a sobra vira a linha que não fechou, destacada em vermelho tracejado logo abaixo, com a conta escrita à mão (`12 ÷ 4 = 3, sobra 0`).

Números grandes têm resposta de desenho, não de escala: quando um kit passa de 11 itens, a linha mostra três marcas e o resumo `… 21 no total`; acima de 12 kits, as linhas seguintes viram `+ N kits iguais a esses`. A conta exibida continua sendo a real.

A escolha do número de kits é uma trilha de 1 a 20, com alvos de toque de 48px. O que funcionou fica verde, o que não funcionou fica riscado — a criança monta sozinha a lista dos divisores comuns, e o MDC é o maior círculo verde. Para estoques do laboratório acima de 20 itens, aparece um campo para digitar qualquer número.

## Recursos

- Funciona offline e sem dependências externas.
- Interface responsiva para computador, tablet e celular.
- Controles grandes, entrada por teclado e mensagens que não dependem somente de cor.
- Dicas progressivas e feedback sem punição excessiva.
- Progresso, estrelas, pontuação e configurações salvos em `localStorage`.
- Nenhum dado é enviado para servidores.

Consulte também a [proposta pedagógica](docs/PROPOSTA-PEDAGOGICA.md) e o [guia do professor](docs/GUIA-DO-PROFESSOR.md).

## Estrutura

```text
.
├── index.html                       # entrada do GitHub Pages
├── missao_kits_da_festa.html       # jogo completo
├── README.md
├── .gitignore
└── docs/
    ├── PROPOSTA-PEDAGOGICA.md
    └── GUIA-DO-PROFESSOR.md
```

## Desenvolvimento local

Não há instalação, compilação ou servidor obrigatório. Abra `index.html` em um navegador moderno. Todo o HTML, CSS e JavaScript do jogo está no arquivo `missao_kits_da_festa.html`.

## Publicação

O repositório público está em [marcelo7bastos/aprendendo-maximo-divisor-comum](https://github.com/marcelo7bastos/aprendendo-maximo-divisor-comum). O GitHub Pages publica a raiz da branch `main`.

Para enviar alterações futuras:

```powershell
git add .
git commit -m "Descreva a alteração"
git push
```

## Licença

Este repositório ainda não define uma licença de reutilização. Antes de receber contribuições externas, o titular deve escolher uma licença apropriada.
