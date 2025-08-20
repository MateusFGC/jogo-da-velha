# Jogo da Velha em JavaScript

Este projeto é uma implementação simples do Jogo da Velha (Tic-Tac-Toe) utilizando JavaScript. O jogo permite que dois jogadores joguem alternadamente, marcando suas jogadas em um tabuleiro virtual.

## Funcionalidades

- **Jogadores Alternados**: O jogo alterna entre dois jogadores, 'X' e 'O'.
- **Detecção de Vitória**: O jogo verifica se um jogador venceu após cada jogada.
- **Empate**: O jogo informa se houve um empate quando não há mais jogadas possíveis.
- **Reinício do Jogo**: O jogo pode ser reiniciado a qualquer momento.

## Estrutura do Código

A lógica do jogo é organizada em funções principais:

- `initializeGame()`: Inicializa o tabuleiro e define o jogador que começa.
- `updateTitle()`: Atualiza o título da página para mostrar de quem é a vez.
- `handleBoardClick(ev)`: Lida com o clique do jogador em uma região do tabuleiro.
- `getWinRegions()`: Verifica se existe uma combinação vencedora.
- `handleWin(regions)`: Exibe as regiões vencedoras e o nome do jogador que ganhou.
- `disableRegion(element)`: Desabilita uma região do tabuleiro após ser clicada.

## Como Usar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/jogo-da-velha.git
   cd jogo-da-velha
2. **Abra o arquivo HTML** no navegador.
3. **Insira os nomes dos jogadores** nos campos apropriados e clique em "Iniciar Jogo" para começar a partida.
4. **Clique nas regiões do tabuleiro** para fazer suas jogadas.

## Tecnologias Utilizadas

- **HTML**: Para a estrutura básica do jogo.
- **CSS**: Para estilização simples do tabuleiro.
- **JavaScript**: Para a lógica do jogo e interação.

## Contribuição

Sinta-se à vontade para contribuir com melhorias, correções ou novas funcionalidades. 


---

Divirta-se jogando! 🎮

https://mateusfgc.github.io/jogo-da-velha/
