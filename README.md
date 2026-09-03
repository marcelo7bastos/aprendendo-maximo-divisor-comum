# Oficina das Fitas — Jogo do MDC

Um jogo educativo, visual e responsivo para explorar o **Máximo Divisor Comum (MDC)** a partir de fitas que precisam ser cortadas em pedaços iguais, sem sobras e no maior tamanho possível.

Em vez de começar por uma fórmula, o jogo segue a sequência pedagógica:

> experimentar → observar → testar → comparar → descobrir → nomear → calcular

O projeto funciona inteiramente no navegador, sem dependências externas, conta ou conexão com a internet.

## Como jogar

Abra [index.html](index.html) no navegador. Ele encaminha para o arquivo principal, [oficina_das_fitas_mdc.html](oficina_das_fitas_mdc.html), que também pode ser aberto diretamente.

Em cada desafio, escolha um tamanho de pedaço, teste o corte nas três fitas e observe se há sobras. Um tamanho só resolve a missão quando divide todas as fitas exatamente; para concluir, é preciso encontrar o **maior** tamanho que funciona.

## Modos disponíveis

- **Trilha de desafios:** dez cartas com progressão da descoberta visual à formalização do MDC.
- **Laboratório:** crie desafios informando três números inteiros de 2 a 1.000.
- **Desafio aleatório:** gere novos conjuntos para praticar sem repetir a trilha. O gerador constrói números com um MDC conhecido e evita conjuntos triviais ou fora do intervalo.

No laboratório, o aleatório oferece limites de 60, 100, 300 ou 1.000 e uma opção avançada para incluir o caso `MDC = 1`.

Para comprimentos de até 100, a interface usa blocos unitários. De 101 a 1.000, passa a usar uma escala comum com, no máximo, 100 marcas por fita e uma visão compacta de grupos e sobra. Assim, o raciocínio visual permanece fiel sem desenhar até mil elementos na tela.

## Recursos pedagógicos

- Feedback que trata a tentativa que deixa resto como investigação, não como punição.
- Confirmação separada para um divisor comum e para o maior divisor comum.
- Dicas progressivas e explicação formal opcional após a descoberta.
- Registro local de fases, estrelas, pontos e configurações no navegador.
- Controles por teclado e layout adaptado para computador, tablet e celular.

Leia também a [proposta pedagógica](docs/PROPOSTA-PEDAGOGICA.md) e o [guia do professor](docs/GUIA-DO-PROFESSOR.md).

## Estrutura do projeto

```text
.
├── index.html                    # entrada para GitHub Pages; encaminha ao jogo
├── oficina_das_fitas_mdc.html    # aplicativo completo (HTML, CSS e JavaScript)
├── README.md
├── .gitignore
└── docs/
    ├── PROPOSTA-PEDAGOGICA.md
    └── GUIA-DO-PROFESSOR.md
```

## Publicação no GitHub

O nome `oficina_das_fitas_mdc.html` é descritivo e foi preservado como arquivo principal. Como o GitHub Pages procura `index.html` na raiz, este projeto inclui uma página inicial mínima que encaminha automaticamente para o jogo.

Para criar o repositório local e enviar os arquivos:

```powershell
git init
git add index.html oficina_das_fitas_mdc.html README.md .gitignore docs
git commit -m "Publica Oficina das Fitas"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/aprendendo-maximo-divisor-comum.git
git push -u origin main
```

Depois, no repositório do GitHub, abra **Settings → Pages**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/(root)`. A página ficará disponível no endereço informado pelo GitHub Pages.

## Desenvolvimento local

Não há instalação, compilação ou servidor obrigatório. Basta abrir o arquivo HTML em um navegador moderno. Se preferir usar um servidor local, qualquer servidor estático serve; ele não deve ser necessário para o funcionamento do jogo.

## Privacidade

O progresso é salvo apenas no `localStorage` do navegador usado. Nenhum dado é enviado a servidores. A opção de reiniciar progresso remove esse registro local.

## Licença e contribuições

Este repositório ainda não define uma licença de reutilização nem um processo formal de contribuições. Antes de torná-lo público para colaboração externa, o titular deve escolher uma licença e, se necessário, acrescentar instruções de contribuição.
