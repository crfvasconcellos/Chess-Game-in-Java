# ♟️ chess-Game – Sistema de Xadrez em Java

Projeto desenvolvido por **[Cláudio Vasconcellos](https://github.com/crfvasconcellos)** e **[Otávio Augusto](https://github.com/otavio-asr)**  
Durante a disciplina de **Programação Orientada a Objetos (POO)** no curso de **Ciência da Computação** da **UFT**.

O objetivo do projeto é implementar um **sistema de xadrez completo em Java**, com **regras reais do jogo**, **tratamento de exceções**, **movimentação das peças**, **verificação de xeque/xeque-mate** e **modo textual** para interação via console.

---

## 🚀 Tecnologias Utilizadas
- **Java** 
- **Paradigma de Programação Orientada a Objetos**
- **Tratamento de Exceções**
- **Estruturas de Dados (Matrizes e Classes)**

---

## 🎯 Funcionalidades Principais
✔️ Movimentação de todas as peças do xadrez  
✔️ Indicação visual do tabuleiro no console  
✔️ Validação de movimentos ilegais  
✔️ Verificação de **Xeque**  
✔️ Verificação de **Xeque-mate**  
✔️ Controle de turnos (brancas x pretas)  
✔️ Captura de peças adversárias  
✔️ Sistema de **posições possíveis** (highlight de movimentos)  

---

## 📌 Organização do Projeto

```
📦 chess-Game
├── 📁 board
│   ├── Board.java
│   ├── Position.java
│   ├── Piece.java
├── 📁 chess
│   ├── ChessMatch.java
│   ├── ChessPiece.java
│   ├── ChessException.java
│   ├── pieces/
│       ├── King.java
│       ├── Pawn.java
│       ├── Rook.java
│       ├── Bishop.java
│       ├── Knight.java
│       ├── Queen.java
└── 📄 Program.java
```

---

## 🎮 Como Executar

### 📍 Pré-requisitos
- Ter o **Java instalado** na máquina.

### ▶️ Rodar o projeto
No terminal, navegue até a pasta do projeto e execute:

```bash
javac Program.java
java Program
```

O sistema exibirá o tabuleiro e solicitará as jogadas via entrada de texto.

---

## 📷 Exemplo de Saída (Tabuleiro no Console)

```
8  ♜ ♞ ♝ ♛ ♚ ♝ ♞ ♜
7  ♟ ♟ ♟ ♟ ♟ ♟ ♟ ♟
6  - - - - - - - -
5  - - - - - - - -
4  - - - - - - - -
3  - - - - - - - -
2  ♙ ♙ ♙ ♙ ♙ ♙ ♙ ♙
1  ♖ ♘ ♗ ♕ ♔ ♗ ♘ ♖
   a  b  c  d  e  f  g  h
```

---

## 🧩 Regras Implementadas

🔹 Peões podem se mover duas casas no primeiro movimento  
🔹 Movimentos especiais como roque *(opcional colocar se está implementado)*  
🔹 Bloqueio de jogadas que deixam o rei em xeque  
🔹 Captura de peças com validação  
🔹 Verificação automática de **Xeque-Mate**

---

## 👨‍💻 Desenvolvedores

| Nome | GitHub |
|------|--------|
| **Cláudio Vasconcellos** | https://github.com/crfvasconcellos |
| **Otávio Augusto** | https://github.com/otavio-asr |

---

## 📝 Licença
Este projeto foi desenvolvido para fins **educacionais**, sem fins comerciais.  
Sinta-se à vontade para estudar, modificar e evoluir o sistema! 😉

---

### ⭐ Dê um star no repositório se gostou!
