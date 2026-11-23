<h1 align="center">✊ Jokenpô</h1>

<p align="center">
  <img src="projeto_imagem.png" width="800" alt="Prévia do jogo Jokenpô">
</p>

<p align="center">
  <b><a href="https://jonataswebj-lab.github.io/Jokenpo/">🔗 Ver site no ar</a></b>
</p>

Jogo de pedra, papel e tesoura contra a máquina, com placar e nome personalizado para o adversário.

## O que o projeto faz
- O jogador escolhe pedra, papel ou tesoura e a máquina sorteia a jogada dela
- Mostra se foi vitória, derrota ou empate e atualiza o placar
- Permite definir (e trocar) o nome do adversário

## Tecnologias
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## O que pratiquei
- Funções separadas: jogada do jogador, jogada da máquina e regra do jogo
- Objeto de constantes (`GAME_OPTIONS`) para evitar erros de digitação
- Sorteio com `Math.random()`
- Condicionais com `&&` e `||`
- Manipulação do DOM e eventos
- Layout responsivo com Flexbox e `@media`

## Próximos passos
- [ ] Mostrar na tela o que a máquina escolheu
- [ ] Usar o nome do adversário também na mensagem de derrota
- [ ] Modo "melhor de 5" e placar salvo no `localStorage`
- [ ] Usar `addEventListener` no lugar do `onclick` no HTML

## Como rodar
Baixe o repositório e abra o `index.html` no navegador.
