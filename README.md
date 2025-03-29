# Sudoku Game

## 📌 Sobre  
Este é um jogo de Sudoku desenvolvido em Java. O objetivo do jogo é preencher um tabuleiro 9x9 com números de 1 a 9, seguindo as regras clássicas do Sudoku:
- Cada linha deve conter todos os números de 1 a 9 sem repetições.
- Cada coluna deve conter todos os números de 1 a 9 sem repetições.
- Cada subgrade 3x3 deve conter todos os números de 1 a 9 sem repetições.

O projeto foi desenvolvido com foco em aprendizado e prática de conceitos de programação orientada a objetos.

---

## 📂 Estrutura do Projeto  
```  
Sudoku/  
│─── src/  
│    ├── Main.java              # Classe principal que gerencia o jogo.  
│    ├── model/  
│    │    ├── Board.java        # Representa o tabuleiro do Sudoku.  
│    │    ├── Space.java        # Representa cada espaço no tabuleiro.  
│    ├── util/  
│    │    ├── BoardTemplate.java # Template para exibição do tabuleiro no terminal.  
│─── README.md                  # Documentação do projeto.  
│─── .gitignore                 # Arquivos ignorados pelo Git.  
```  

---

## 📝 Descrição dos Arquivos
- **Main.java**: Contém a lógica principal do jogo, incluindo o menu interativo e as opções para iniciar, visualizar e manipular o tabuleiro.
- **Board.java**: Classe que representa o tabuleiro do Sudoku, incluindo métodos para verificar o status do jogo e manipular os valores.
- **Space.java**: Classe que representa cada espaço no tabuleiro, armazenando o valor atual e se ele é fixo ou não.
- **BoardTemplate.java**: Contém o template usado para exibir o tabuleiro no terminal.

---

## ⚙️ Funcionalidades  
- **Iniciar um novo jogo**: Cria um novo tabuleiro com valores iniciais.
- **Inserir um número**: Permite ao jogador inserir um número em uma posição específica.
- **Remover um número**: Remove um número de uma posição específica, se permitido.
- **Visualizar o tabuleiro**: Exibe o estado atual do tabuleiro no terminal.
- **Verificar status do jogo**: Mostra se o jogo está completo ou contém erros.
- **Limpar o jogo**: Reseta o tabuleiro para o estado inicial.
- **Finalizar o jogo**: Encerra o jogo.

---

## 🛠️ Tecnologias Utilizadas  
- **Java** - Linguagem de programação principal.  
- **Visual Studio Code** - Ambiente de desenvolvimento utilizado.  
- **Git** - Controle de versão para gerenciamento do código-fonte.  

---

## 🎯 Conceitos Utilizados  
- **Programação Orientada a Objetos (POO)**: Uso de classes como `Board` e `Space` para modelar o jogo.
- **Streams e Lambdas**: Utilizados para manipulação de coleções e argumentos.
- **Tratamento de Exceções**: Garantindo que o programa lide com entradas inválidas e erros de forma robusta.
- **Design Modular**: Separação de responsabilidades entre as classes.

---

## 🚀 Como Executar  
1. Clone o repositório:
   ```bash
   git clone https://github.com/JoaoAzevedo184/sudoku-game.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd sudoku-game
   ```
3. Compile o projeto:
   ```bash
   javac -d bin src/**/*.java
   ```
4. Execute o jogo:
   ```bash
   java -cp bin Main
   ```

---

## 👤 Autor  
Desenvolvido por João Azevedo. Para mais informações, entre em contato:   
- **Gmail**: jonoffice37@gmail.com  
- **Linkedin**: [João Victor Azevedo](https://www.linkedin.com/in/joao-victor-azevedo-181-sena)  
- **Github**: [JoaoAzevedo184](https://github.com/JoaoAzevedo184)

---