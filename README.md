# 🐍 Snake Game — Jogo da Cobrinha

Um jogo da cobrinha (*Snake Game*) desenvolvido para navegadores, inspirado no clássico jogo de arcade. O projeto apresenta uma interface moderna e responsiva, com controles adaptados para computadores e dispositivos móveis.

O objetivo é controlar a cobrinha, coletar os alimentos, aumentar sua pontuação e evitar colisões com as paredes ou com o próprio corpo.

## 🎮 Funcionalidades

- **Sistema de pontuação:** acumule pontos ao coletar alimentos.
- **Recorde pessoal:** armazena automaticamente a maior pontuação utilizando `localStorage` do navegador.
- **Velocidade progressiva:** a velocidade da cobrinha aumenta conforme a pontuação.
- **Sistema de pausa:** pause e continue a partida quando desejar.
- **Reiniciar partida:** comece um novo jogo a qualquer momento.
- **Detecção de colisões:** identifica colisões com as paredes e com o próprio corpo.
- **Condição de vitória:** permite vencer ao preencher todo o tabuleiro.
- **Controles multiplataforma:** suporte para teclado, botões direcionais e gestos de deslizar (*swipe*).
- **Interface responsiva:** adapta-se a diferentes tamanhos de tela.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| HTML5 | Estrutura e organização dos elementos da página. |
| CSS3 | Estilização, layout, animações e responsividade. |
| JavaScript (Vanilla) | Lógica do jogo, movimentação, pontuação e interações. |
| Canvas API | Renderização gráfica do tabuleiro, cobrinha e alimentos. |
| LocalStorage | Armazenamento local do recorde do jogador. |
| RequestAnimationFrame | Controle do ciclo de atualização e renderização do jogo. |

## 🕹️ Como jogar

O objetivo é controlar a cobrinha para coletar os alimentos que aparecem aleatoriamente pelo tabuleiro.

Cada alimento coletado aumenta a pontuação e o comprimento da cobrinha. Entretanto, é necessário evitar colisões com as paredes e com o próprio corpo.

### Controles

| Ação | Teclas |
|---|---|
| Mover para cima | `↑` ou `W` |
| Mover para baixo | `↓` ou `S` |
| Mover para esquerda | `←` ou `A` |
| Mover para direita | `→` ou `D` |
| Pausar / Continuar | `Espaço` ou `P` |
| Iniciar / Reiniciar | `Enter` ou botão na interface |

**Dispositivos móveis:** utilize os botões direcionais exibidos na tela ou deslize o dedo sobre o tabuleiro para controlar a direção da cobrinha.

## 🚀 Como executar

O projeto não necessita de instalação de dependências ou configuração de ambiente.

1. Faça o download ou clone este repositório.
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` em um navegador.
4. Clique em **Começar jogo** e divirta-se!

## 📁 Estrutura do projeto

```text
Snake-Game/
│
└── index.html
```

Todo o projeto está concentrado em um único arquivo HTML, contendo a estrutura da página, os estilos CSS e a lógica JavaScript.

## 💡 Características técnicas

- Tabuleiro com grade de **24 × 24 células**.
- Renderização em um elemento HTML Canvas de **480 × 480 pixels**.
- Movimentação baseada em intervalos de tempo e `requestAnimationFrame`.
- Aumento progressivo da velocidade a cada cinco pontos.
- Velocidade limitada para manter a jogabilidade.
- Armazenamento do recorde no próprio navegador, sem necessidade de banco de dados ou servidor.

## 📌 Considerações

Este projeto foi desenvolvido com foco na prática de desenvolvimento web, utilizando tecnologias fundamentais da programação Front-End.

A proposta é oferecer uma experiência simples, intuitiva e acessível, mantendo a essência do clássico Snake Game com melhorias na interface e nos controles.

---

**Desenvolvido com HTML5, CSS3 e JavaScript.**
