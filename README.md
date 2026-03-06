<div align="center"> 
  
### 🐄 Freeway: Atravesse a Estrada!

Este é um jogo clássico inspirado no antigo Freeway do Atari. O objetivo é simples, mas desafiador: ajude a vaquinha a atravessar a estrada movimentada sem ser atingida pelos carros. Cada travessia bem-sucedida garante um ponto, mas um atropelamento te manda de volta para o começo!

### 🕹️ Como Jogar

O jogo é controlado inteiramente pelo teclado:

    Seta para Cima (↑): Move a vaca para frente.
    Seta para Baixo (↓): Move a vaca para trás (dentro do limite da tela).
    Objetivo: Chegar ao topo da tela para marcar pontos.

### 🚀 Tecnologias Utilizadas

O projeto foi desenvolvido utilizando a biblioteca p5.js, focando em lógica de programação e manipulação de arrays/objetos em JavaScript.

    p5.js - Biblioteca principal para desenho e animação.
    p5.collide2D - Biblioteca auxiliar para detecção de colisões.
    JavaScript - Lógica principal e estruturação.

### 🛠️ Funcionalidades do Código
<pre>
Sistema de Colisão: Utiliza a função collideRectCircle para detectar o impacto entre os carros (retângulos) e a vaca (círculo).
Movimentação Infinita: Os carros reaparecem no lado direito da tela assim que saem pelo lado esquerdo.
Pontuação Dinâmica: Um placar em tempo real que aumenta ao vencer a estrada e diminui em caso de colisão (sem nunca ficar negativo).
Efeitos Sonoros: Trilhas sonoras imersivas e sons de feedback para pontos e colisões.
</pre>

### 📂 Estrutura de Arquivos
  <pre>
  sketch.js: O coração do jogo, onde o loop principal (draw) acontece.
  ator.js: Define as propriedades e movimentos do nosso personagem.
  carro.js: Gerencia o comportamento, velocidade e posição dos veículos.
  imagens.js: Centraliza o carregamento de todos os assets (sons e imagens).
  p5.collide2d.js: Biblioteca externa para facilitar as colisões.
  </pre>  

### 🎨 Preview
   ![travessandoarua](https://github.com/user-attachments/assets/0102bb7f-cf9c-4ec3-9124-6680ede738f2)

  ## Linguagem Utilizada:
<div style="display: inline_block"><br>

| Javascript |
| :---: |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="80" /> |

# Autora:

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/142232479?v=4" width=115><br><sub>Luiza Hackenhaar Naziazeno</sub>](https://github.com/luizahackenhaarnaziazeno)|
| :---: |
