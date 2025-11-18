# ♟️ Chess-Game – Jogo de Xadrez em Java

Projeto desenvolvido por **[Cláudio Vasconcellos](https://github.com/crfvasconcellos)** e **[Otávio Augusto](https://github.com/otavio-asr)** como **trabalho final da disciplina de Programação Orientada a Objetos (POO)** ministrada pelo **Professor David Nadler Prata** na **Universidade Federal do Tocantins (UFT)**.

O projeto tem como objetivo aplicar, na prática, os princípios da POO utilizando Java, incluindo herança, polimorfismo, encapsulamento, tratamento de erros e regras completas do jogo de xadrez.

---

## 📌 Descrição

**Chess-Game** é um jogo de xadrez completo executado no console, permitindo que dois jogadores disputem uma partida com todas as regras oficiais da modalidade.  
O sistema inclui:

- Representação completa do tabuleiro  
- Todas as peças do xadrez com seus movimentos reais  
- Sistema de turno entre jogadores  
- Verificação de xeque e xeque-mate  
- Peças capturadas exibidas separadamente  
- Tratamento de exceções e entradas inválidas  
- Jogadas especiais:
  - **Roque**
  - **En Passant**
  - **Promoção de Peão**

---

## 🧱 Tecnologias Utilizadas

- Java 17+  
- Programação Orientada a Objetos (POO)  
- ANSI Colors no console  
- Arquitetura em camadas (boardgame / chess / application)

---

## 🚀 Como rodar o projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-repositorio-aqui.git
   ```

2. **Abra o projeto no IntelliJ, Eclipse ou VS Code com extensão Java.**

3. **Execute a classe principal:**
   ```
   application/Program.java
   ```

4. O jogo será exibido diretamente no console.

---

## 📁 Estrutura do Projeto

```bash
Chess-Game/
│
├── src/
│   ├── application/        # Interface com o usuário (UI/console)
│   │   └── Program.java
│   │
│   ├── boardgame/          # Lógica genérica de tabuleiro e peças
│   │   ├── Board.java
│   │   ├── Piece.java
│   │   ├── Position.java
│   │   └── BoardException.java
│   │
│   └── chess/              # Regras específicas do xadrez
│       ├── ChessMatch.java
│       ├── ChessPiece.java
│       ├── ChessPosition.java
│       ├── King.java
│       ├── Queen.java
│       ├── Rook.java
│       ├── Bishop.java
│       ├── Knight.java
│       └── Pawn.java
│
└── README.md
```

---

## 🏆 Funcionalidades em destaque

- **Movimentação real das peças**  
- **Possíveis movimentos destacados no console**  
- **Sistema de turnos**  
- **Xeque e Xeque-mate**  
- **Peças capturadas listadas separadamente**  
- **Jogadas especiais:**
  - Roque pequeno e grande  
  - En Passant  
  - Promoção de Peão  

---

## 🧪 Exemplo de Execução

```
8  r - - - k - - r
7  p p p p - p p p
6  - - - - - - - -
5  - - - - - - - -
4  - - - - - - - -
3  - - - - - - - -
2  P P P P P P P P
1  R N B Q K B N R
   a b c d e f g h

Turn: White
Source: e2
Target: e4
```

---

## ⚠️ Observações

- Desenvolvido para fins didáticos  
- Interface apenas via console  
- Não possui IA — apenas dois jogadores humanos

---

## 👨‍💻 Autores

- **[Cláudio Vasconcellos](https://github.com/crfvasconcellos)**
- **[Otávio Augusto](https://github.com/otavio-asr)**

