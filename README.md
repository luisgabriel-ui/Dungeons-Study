# Campus Rush

# Descrição do Projeto
Race for Approval é um jogo 2D em pixel art, feito em Python com Pygame, em que um aluno corre pela avenida da faculdade tentando “ganhar aprovação” ao coletar códigos e desviar de obstáculos como carros, PDFs e cobras.​
O objetivo é sobreviver o máximo possível, mantendo as vidas e acumulando pontos até alcançar a pontuação de vitória.

# Recursos Principais
Sistema de cenas com tela inicial, jogo, tela de derrota e tela de vitória, todas com imagens próprias.​

Fundo rolando continuamente para simular movimento da rua e sensação de corrida infinita.​

Obstáculos e itens gerados em posições aleatórias, com diferentes velocidades de queda.

# Objetivos Educacionais
Praticar conceitos de programação orientada a objetos em Python (classes, herança e encapsulamento).​

Aplicar lógica de jogos: detecção de colisão, contagem de pontos, sistema de vidas e condições de vitória/derrota.​

Exercitar o uso da biblioteca Pygame para criação de janelas, sprites, eventos de teclado e game loop.​

# Tecnologias Utilizadas
Linguagem: Python 3.​

Biblioteca: Pygame (renderização 2D, sprites, eventos e relógio de FPS).​

Assets: sprites e telas em pixel art (personagem, obstáculos, fundo, tela inicial, game over e vitória).​

# Estrutura Básica do Código
main.py: ponto de entrada do jogo; cria a janela, controla o loop principal, troca entre menu, jogo, game over e vitória.​

menu.py: define as classes de cena Menu, Gameover e Vitoria, responsáveis por desenhar as telas estáticas e reagir a teclas.​

game.py: implementa a classe Game, que gerencia fundo rolando, criação/movimento de obstáculos, HUD, colisões e regras de vitória/derrota.​

obj.py: contém a classe genérica Obj, a classe de texto Texto (HUD) e o Player, com movimento lateral, pontos e vidas.​

Pasta assets/: imagens do cenário, personagem, obstáculos, HUD e telas de menu, vitória e derrota.​

# Como Executar
Instale o Python 3 em seu computador.​

Instale o Pygame com: pip install pygame.​

Baixe/clon e este repositório, garantindo que a pasta assets/ esteja no mesmo nível dos arquivos main.py, game.py, menu.py e obj.py.​

No terminal, dentro da pasta do projeto, execute: python main.py.​

Na tela inicial, pressione qualquer tecla para começar; use as setas esquerda e direita para mover o aluno, colete os ícones de código e desvie dos PDFs, cobras e carros.

# Contribuições
Contribuições são bem-vindas! Por favor, crie issues para reportar bugs ou sugerir melhorias e envie pull requests para novas funcionalidades ou correções.
