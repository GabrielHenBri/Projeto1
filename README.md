# Projeto-1-Numpy

# Jogo de Caça ao Tesouro

## Descrição
Este é um jogo simples baseado em terminal onde o jogador precisa encontrar um tesouro escondido em um mapa 5x5. O jogo gera um mapa aleatório e posiciona o tesouro em uma posição aleatória (exceto na posição inicial do jogador). O jogador pode se mover pelo mapa utilizando comandos de direção até encontrar o tesouro.

## Funcionalidades
- Gera um mapa 5x5 com valores aleatórios.
- Posiciona o jogador na posição inicial (0,0).
- Posiciona o tesouro em um local aleatório diferente da posição inicial.
- Permite movimentação do jogador pelo mapa usando comandos de direção.
- Exibe o mapa atualizado a cada movimento.
- Finaliza o jogo quando o jogador encontra o tesouro, exibindo a pontuação final.

## Requisitos
- Python 3.x
- Biblioteca NumPy

## Instalação
1. Clone este repositório ou copie o código para sua máquina.
2. Instale a biblioteca NumPy, caso ainda não tenha:
   ```bash
   pip install numpy
   ```
3. Execute o script:
   ```bash
   python jogo_tesouro.py
   ```

## Como Jogar
1. O jogo exibirá um mapa com valores aleatórios.
2. O jogador deve inserir um dos seguintes comandos para se movimentar:
   - `cima` ou `c`
   - `baixo` ou `b`
   - `esquerda` ou `e`
   - `direita` ou `d`
3. Se o movimento for inválido (fora do mapa), o jogo avisará e solicitará uma nova entrada.
4. O jogo termina quando o jogador encontra o tesouro, exibindo sua pontuação final.

## Exemplo de Execução
```bash
Mapa Atual:
 4  7  2  8  6
 5  3  9  1  2
 7  5  4  6  8
 1  9  3  7  5
 2  6  8  4  9

Informe a direção que deseja mover (cima, baixo, esquerda, direita): direita
```

## Autor
Desenvolvido por [Seu Nome].

## Licença
Este projeto está sob a licença MIT.

