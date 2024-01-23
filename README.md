# Chess System in Java

Este é um simples jogo de xadrez em Java que permite aos jogadores jogarem pelo terminal. O projeto está organizado em três pastas principais:

## Estrutura do Projeto

### 1. application/

Esta pasta contém a classe principal do programa que inicializa e executa o jogo.

- **Program**: A classe principal que inicia a aplicação e gerencia o loop principal do jogo.
- **UI**: Contém classes relacionadas à interface do usuário, como a exibição do tabuleiro no console.

### 2. boardgame/

Esta pasta contém as classes relacionadas ao tabuleiro de xadrez.

- **Board**: Representa o tabuleiro de xadrez, mantendo as peças e gerenciando as jogadas.
- **BoardException**: Uma exceção personalizada para lidar com erros no tabuleiro.
- **Piece**: Uma classe abstrata que representa uma peça no xadrez.
- **Position**: Representa uma posição no tabuleiro.

### 3. chess/

Esta pasta contém as classes específicas do xadrez, como peças e regras do jogo.

#### chess/pieces/

- **Bishop**: Representa a peça Bispo no xadrez.
- **King**: Representa a peça Rei no xadrez.
- **Knight**: Representa a peça Cavalo no xadrez.
- **Pawn**: Representa a peça Peão no xadrez.
- **Queen**: Representa a peça Rainha no xadrez.
- **Rook**: Representa a peça Torre no xadrez.

#### chess/

- **ChessException**: Exceção personalizada para lidar com erros específicos do xadrez.
- **ChessMatch**: Classe principal que gerencia o estado do jogo e as jogadas.
- **ChessPiece**: Extensão da classe Piece, representando peças específicas do xadrez.
- **ChessPosition**: Extensão da classe Position, representando posições específicas do xadrez.
- **Color**: Enumeração que representa as cores das peças no xadrez (WHITE, BLACK).

## Como Jogar

1. Compile e execute o programa Java.
2. Siga as instruções no console para realizar as jogadas.
3. O jogo exibe o tabuleiro após cada jogada e informa se houve algum vencedor.

## Observações

- Certifique-se de ter uma máquina virtual Java (JVM) instalada para executar o programa.
- Este é um jogo de xadrez simplificado, projetado para ser jogado no terminal. Personalize conforme necessário para atender às suas preferências ou expandir funcionalidades.

Divirta-se jogando xadrez!
