# 👾 AGRINHO OS v2.026

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![HTML5 / CSS3 / JS](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20JS-orange.svg)](https://developer.mozilla.org/pt-BR/)

Um site basedo no estilo retrô simulado diretamente no navegador ( Anos 90), e com estilo em pixel art desenvolvido para o **Projeto Agrinho 2026**.

( **para uma melhor experiência, certifique-se de colocar o site em tela cheia** ) 

---

## 📌 Objetivos do Texto e do Projeto

O objetivo central do **AGRINHO OS** é atuar como uma plataforma digital interativa e explicativa. Ele utiliza a estética de computadores antigos para criar um sentimento de nostalgia para o usuário enquanto transmite dados históricos e geográficos essenciais sobre o agronegócio paranaense.

* **Resgate Histórico:** Documentar a evolução do campo, desde a crise da cafeicultura e os impactos climáticos das décadas passadas até a era moderna da Inteligência Artificial.
* **Conscientização Regional:** Destacar as microrregiões produtoras do Paraná, detalhando a distribuição de cereais, legumes e plantas industriais.
* **Sustentabilidade:** Demonstrar visualmente que o futuro e a alta produtividade agrícola dependem diretamente do equilíbrio ecológico e da biotecnologia.

---

## 🎮 Informações sobre o Jogo (`JOGO.EXE`)

Integrado diretamente ao código do site, o **Agro Valley** é um simulador de fazenda em estilo *pixel art* 2D. 

### 🎯 Objetivos do SIte
Para vencer o jogo o jogador deve cumprir 4 missões principais:
1.  **Arar, plantar e regar:** Preparar a terra e iniciar o ciclo de cultivo.
2.  **Dormir na cama:** Avançar o tempo (ciclo dia/noite) para que as plantas cresçam.
3.  **Colher e vender:** Recolher o fruto do trabalho e transformá-lo em receita.
4.  **Conseguir 1000G:** Acumular dinheiro através de uma gestão de safra eficiente.

### 🕹️ Comandos e Controles
* `W, A, S, D` — Movimentar o personagem.
* `Clique Esquerdo do Mouse` — Utilizar ferramentas (Arar com a Enxada `⛏️`, Plantar Sementes `🌱`, Regar com Água `💧` e Colher).
* `Teclas 1 a 6` ou `Setas Direcionais` — Seleção rápida de itens da barra de ferramentas (*hotbar*).
* `Tecla E` — Interagir com o ambiente (entrar na casa, usar o terminal ou dormir).
* `Tecla I` — Abrir/fechar a mochila de inventário (suporta *Drag & Drop* de itens).
* `ESC` — Fechar janelas abertas de terminal ou inventário.

---

## 🌾 Descrição do Tema Central

O projeto aborda a **"Evolução Sustentável e o Rumo ao Campo Digital"** dividindo-se em três pastas informativas principais encontrados nos arquivos `.doc` do desktop:

### 1. Evolução Histórica (`Evolucao_Sustentavel.doc`)
* **Anos 60:** O domínio do café (50% da produção nacional), os grandes incêndios florestais de 1963 e o início da diversificação de culturas.
* **Anos 70:** O trágico fenômeno da **"Geada Negra" em 18 de julho de 1975**, que dizimou a economia cafeeira e forçou a mecanização drástica e diversificação do campo.
* **Anos 10 e 20+:** A consolidação de novas regiões e a transição definitiva para a Era da Inteligência Artificial e Biotecnologia aplicada no Paraná.

### 2. Safra de Legumes e Cereais (`Safra_Parana.doc`)
Apresenta dados de cultivo e aponta as microrregiões líderes no estado:
* **Arroz:** Principalmente arroz de sequeiro (Guarapuava, Paranavaí, Campo Mourão).
* **Milho:** Gramínea altamente benéfica para alimentação humana e animal (Toledo, Cascavel, Francisco Beltrão).
* **Trigo e Cereais de Inverno:** Culturas de solo e clima específicos, incluindo o avanço da Cevada, Aveia e Centeio (Guarapuava, Ponta Grossa).

### 3. Plantas Industriais (`Plantas_Industriais.doc`)
* **Cana-de-Açúcar:** Expansão no norte paranaense para abastecer a indústria de açúcar e álcool (Paranavaí, Londrina).
* **Algodão:** Cultivado nas ricas terras roxas do norte e oeste (Toledo, Campo Mourão).
* **Rami:** Fibra têxtil de alta resistência introduzida pioneiramente pela imigração japonesa.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web puras (*Vanilla Architecture*), garantindo leveza e portabilidade:
* **HTML5 Semântico:** Estruturação das janelas e do container do jogo.
* **CSS3 Avançado:** Filtros de varredura CRT, animação de *flicker* (cintilação de monitor antigo) e efeito Matrix digital feito via folha de estilo e variáveis latentes.
* **JavaScript (ES6):** Manipulação de DOM para o sistema de janelas arrastáveis (*Drag & Drop*), renderização física do jogo em `HTML5 Canvas` e um **Sintetizador de Áudio Retro** construído sob a API nativa `AudioContext` para emular bips de computadores antigos de forma dinâmica.


