# Mario Jump 🍄

Um minigame estilo "Endless Runner" inspirado no clássico Super Mario, desenvolvido inteiramente com as tecnologias web fundamentais: HTML5, CSS3 e JavaScript (Vanilla). O jogo consiste em ajudar o Mario a desviar dos canos que se aproximam, com a dificuldade (velocidade) aumentando progressivamente.

## 🚀 Funcionalidades e Lógica do Jogo

Este projeto foi construído para praticar e demonstrar habilidades em manipulação de DOM, gerenciamento de estado e eventos no navegador.

* **Sistema de Colisão (Hitbox):** Implementado através de um loop de verificação (em `setInterval` de 10ms) que calcula continuamente a posição absoluta (X e Y) do Mario e do obstáculo na tela.
* **Física e Animações:** Pulos controlados por animações `@keyframes` no CSS e classes ativadas por eventos de teclado (JavaScript), com tempo de *cooldown* exato usando `setTimeout`.
* **Dificuldade Progressiva:** A velocidade da animação do cano diminui (tornando o jogo mais rápido) de forma dinâmica através de um intervalo no JavaScript, exigindo reflexos mais rápidos do jogador ao longo do tempo.
* **Sistema de Pontuação e Áudio:** Contabilização de pontuação contínua, com efeitos sonoros disparados via **HTML Audio API** durante o pulo, *Game Over* e a cada 100 pontos atingidos.

## 💻 Tecnologias Utilizadas

* **HTML5:** Estruturação semântica do jogo e das telas de menu.
* **CSS3:** Estilização, layout e, principalmente, controle de animações nativas (`@keyframes`) para o movimento do cenário e ações dos personagens.
* **JavaScript (Vanilla):** Lógica do jogo, escuta de eventos (`addEventListener`), cálculos de posição (`getComputedStyle`), manipulação de classes e reprodução de mídias.

## 🎮 Como Jogar

1. Ao abrir o jogo, clique no botão **START**.
2. Pressione qualquer tecla do teclado para fazer o Mario pular.
3. Desvie dos canos verdes.
4. Caso esbarre no cano, o jogo para e exibe a tela de *Game Over*. Clique em **Restart** para tentar novamente!

## 🔧 Como Executar Localmente

Como o projeto não utiliza ferramentas de *build* ou frameworks complexos, rodá-lo é extremamente simples:

1. Clone este repositório em sua máquina:
```bash
git clone https://github.com/ojuangoncalves/mario-jump.git
```

2. Acesse a pasta do projeto:
```bash
cd mario-jump
```

3. Abra o arquivo `index.html` em qualquer navegador web de sua preferência. 

*(Alternativamente, você pode usar a extensão "Live Server" do VS Code para executá-lo com auto-reload).*

---
Desenvolvido por [Juan Gonçalves Nascimento](https://github.com/ojuangoncalves)
