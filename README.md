# Jornada do Mamute 🦣🌋

Um jogo de corrida infinita dinâmico e viciante inspirado no clássico *T-Rex Runner* do Google Chrome. O projeto traz uma ambientação pré-histórica única com mecânicas modernas de evolução visual do personagem em tempo real, desenvolvido inteiramente com **HTML5 Canvas** e **JavaScript puro (Vanilla JS)**.

---

## 🎮 Como Jogar

O jogo foi totalmente adaptado e otimizado para rodar perfeitamente tanto em computadores quanto em dispositivos móveis:

* **No Computador:** Pressione a barra de **Espaço** ou a **Seta para Cima (↑)** para fazer o mamute pular os obstáculos.
* **No Celular / Tablet:** Basta **dar um toque em qualquer lugar da tela** para saltar.
* **Reiniciar o Jogo:** Caso perca suas vidas, pressione **Espaço** (computador) ou **toque na tela** (celular) para recomeçar instantaneamente.

---

## 🧬 Sistema de Evolução por Fases

A grande diferença da **Jornada do Mamute** é o sistema de progressão. O seu personagem muda de design digital e o cenário altera o clima dinamicamente conforme você sobrevive e pontua:

1. **Fase 1 (0 a 9 pontos):** Você inicia com o Mamute em formato Pixel Art sob um fundo azul de nevasca clara.
2. **Fase 2 (10 a 19 pontos):** O mamute ganha traços detalhados e o cenário muda para um tom amarelado de entardecer.
3. **Fase 3 (20 a 29 pontos):** O clima esquenta para um deserto alaranjado. O mamute corre tão rápido que começa a levantar poeira e terra realista pelos cascos.
4. **Fase 4 (30 pontos ou mais):** O mamute atinge sua evolução máxima com um visual estilo Cartoon Clássico em meio a uma selva esverdeada.

---

## ⚙️ Funcionalidades Principais

* **Barra de Vidas:** Você inicia a jornada com **3 Corações (❤️)**, dando margem para cometer erros sem sofrer Game Over imediato.
* **Imunidade ao Dano:** Ao colidir com um obstáculo, o mamute pisca e ganha 1,5 segundos de invulnerabilidade para você restabelecer o ritmo.
* **Obstáculos Aleatórios:** Uma fauna e flora variada surge dinamicamente da direita para a esquerda (animais, plantas tropicais, cactos e perigos climáticos).
* **Velocidade Progressiva:** O jogo acelera automaticamente a cada 5 pontos para testar seus reflexos.
* **Recorde Persistente (High Score):** Sua maior pontuação fica salva no navegador (`localStorage`), mantendo seu recorde mesmo se você fechar a aba.
* **Sons Sintetizados:** Efeitos sonoros retrô gerados diretamente via código (*Web Audio API*), eliminando a necessidade de carregar arquivos de áudio externos.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Canvas:** Renderização gráfica de alta performance para jogos rodarem direto no navegador.
* **CSS3:** Design minimalista, responsivo e com travas de segurança para impedir zoom acidental em telas *touch*.
* **JavaScript (ES6):** Lógica de física de gravidade, gerenciamento do loop do jogo (`requestAnimationFrame`) e detecção precisa de colisões baseada em Hitboxes.

---

## 📜 Propriedade Intelectual e Uso Livre

Este projeto foi construído para fins educacionais e de portfólio. As mecânicas de corrida com rolagem lateral e pulos são de domínio público. Toda a arte dos mamutes e partículas de ambiente são geradas de forma autoral via código matemático nativo do navegador, tornando o projeto 100% independente de links ou servidores externos.

---
Prepare-se para guiar o gigante pré-histórico nesta jornada! Boa jogada! 🚀
