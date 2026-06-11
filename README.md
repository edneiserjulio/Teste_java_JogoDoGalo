Jogo do Galo ❌⭕

Um jogo do galo clássico desenvolvido em Java Swing, com interface gráfica, painel de pontuação e um desafio de aprendizagem integrado para quem quiser estender o projeto.


Funcionalidades

FuncionalidadeDescrição🎮 Dois jogadoresJogar localmente como Jogador 1 (X) e Jogador 2 (O)🔵🟢 Feedback visualX aparece a azul, O aparece a verde🏆 Painel de pontuaçãoBarra lateral que regista os pontos de cada jogador🔄 Novo JogoReinicia o tabuleiro sem apagar a pontuação💡 Botão PromptApresenta um desafio guiado para extender o jogo


Como Começar

Pré-requisitos


Java Development Kit (JDK) 8 ou superior
Qualquer IDE Java (IntelliJ IDEA, Eclipse, VS Code com extensão Java) ou terminal


Executar o projeto

Pelo terminal:

bash# Compilar
javac JogoGalo.java

# Executar
java JogoGalo

Pela IDE:
Abrir JogoGalo.java e executar o método main diretamente.


Estrutura do Projeto

JogoGalo/
└── JogoGalo.java   # Classe principal — lógica do jogo, interface e eventos


Como Jogar


Iniciar a aplicação.
Os jogadores jogam à vez, clicando numa célula vazia da grelha 3×3.
O Jogador 1 joga com X (azul) e o Jogador 2 joga com O (verde).
Vence o primeiro jogador que alinhar três símbolos em linha, coluna ou diagonal.
Clicar em New Game para reiniciar o tabuleiro e começar uma nova ronda.



Desafio de Aprendizagem

Este projeto inclui um botão Prompt que apresenta um desafio guiado para extender o jogo com lógica de contagem de pontos. Foi concebido como exercício prático para quem está a aprender Java e Swing.

O desafio propõe:


Incrementar a pontuação do Jogador 1 quando X ganhar
Incrementar a pontuação do Jogador 2 quando O ganhar
Atualizar automaticamente os labels de pontuação após cada vitória
Garantir que o botão New Game reinicia apenas o tabuleiro, sem apagar os pontos



Tecnologias Utilizadas


Java — linguagem principal
Java Swing — framework gráfico (JFrame, JPanel, JButton, JLabel)
AWT — gestores de layout e utilitários de cor (GridLayout, BorderLayout, Color)



Licença

Este projeto é open source e está disponível sob a Licença MIT.


Autor

Desenvolvido como projeto de aprendizagem para praticar desenvolvimento de interfaces gráficas com Java Swing.
