# 🎮 Jogo do Galo (Tic-Tac-Toe) em Java Swing

## 📖 Descrição

Este projeto consiste numa implementação gráfica do clássico **Jogo do Galo (Tic-Tac-Toe)** desenvolvida em **Java** utilizando a biblioteca **Swing** para a construção da interface gráfica.

A aplicação permite que dois jogadores disputem partidas alternadamente através de um tabuleiro 3x3, com indicação visual das jogadas através de diferentes cores para cada símbolo.

---

## ✨ Funcionalidades

* Interface gráfica desenvolvida com Java Swing.
* Tabuleiro 3x3 totalmente interativo.
* Alternância automática entre os jogadores:

  * **Player 1 → X (Azul)**
  * **Player 2 → O (Verde)**
* Sistema de Score preparado para contabilização de pontos.
* Botão **New Game** para reiniciar o tabuleiro.
* Botão **Prompt** com instruções para futuras melhorias.
* Interface organizada através de layouts Swing.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição                      |
| ---------- | ------------------------------ |
| Java       | Linguagem principal do projeto |
| Swing      | Interface gráfica (GUI)        |
| AWT        | Gestão de componentes gráficos |
| JFrame     | Janela principal da aplicação  |
| JButton    | Botões do tabuleiro            |
| JLabel     | Exibição do score              |
| JPanel     | Organização dos componentes    |

---

## 📂 Estrutura do Projeto

```text
JogoGalo.java
│
├── JFrame (Janela Principal)
│
├── Painel Tabuleiro (3x3)
│   ├── JButton[9]
│   ├── Jogador X
│   └── Jogador O
│
├── Painel Score
│   ├── Player 1
│   └── Player 2
│
└── Painel de Controlo
    ├── Prompt
    └── New Game
```

---

## 🚀 Como Executar

### Pré-requisitos

* Java JDK 8 ou superior instalado.

Verificar a instalação:

```bash
java -version
javac -version
```

### Compilar

```bash
javac JogoGalo.java
```

### Executar

```bash
java JogoGalo
```

---

## 🎯 Funcionamento

1. A aplicação inicia com um tabuleiro vazio.
2. O primeiro jogador utiliza o símbolo **X**.
3. O segundo jogador utiliza o símbolo **O**.
4. Cada casa do tabuleiro só pode ser preenchida uma vez.
5. O botão **New Game** limpa o tabuleiro para uma nova partida.
6. O score permanece visível na lateral da aplicação.

---

## 🎨 Convenção de Cores

| Jogador  | Símbolo | Cor   |
| -------- | ------- | ----- |
| Player 1 | X       | Azul  |
| Player 2 | O       | Verde |

---

## 📸 Interface

```text
+---------------------+------------------+
|                     |      Score       |
|       X | O | X     |                  |
|      -----------    |  Player 1 : 0    |
|       O | X | O     |  Player 2 : 0    |
|      -----------    |                  |
|       X |   | O     |   [ Prompt ]     |
|                     | [ New Game ]     |
+---------------------+------------------+
```

---

## 🔄 Melhorias Futuras

* Implementação da deteção automática de vitória.
* Atualização automática do score.
* Verificação de empate.
* Reinício automático após vitória.
* Escolha do jogador inicial.
* Histórico de partidas.
* Modo Jogador vs Computador.
* Interface visual melhorada.

---

## 📚 Conceitos Aplicados

* Programação Orientada a Objetos (POO)
* Eventos e Listeners
* Interfaces Gráficas (GUI)
* Layout Managers
* Manipulação de Componentes Swing
* Gestão de Estado da Aplicação

---

## 👨‍💻 Autor

Projeto desenvolvido para fins académicos e de aprendizagem da linguagem Java e da biblioteca Swing.

**Autor:** Edneiser Júlio

---

## 📄 Licença

Este projeto é disponibilizado para fins educativos e académicos.
