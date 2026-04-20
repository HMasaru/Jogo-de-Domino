# Jogo de Dominó

> 🎓 **Projeto Acadêmico**
> Repositório destinado aos projetos e atividades desenvolvidos para o curso de **Ciência da Computação da PUC**.

Implementação em **C++** de um Jogo de Dominó clássico. 

Para garantir um código organizado e de fácil manutenção, a estrutura do projeto foi dividida utilizando o padrão arquitetural **MVC (Model-View-Controller)**:

* **Model (`_Model.cpp/h`)**: Responsável por gerenciar as regras de negócio, como a lógica das peças, o monte, as mãos dos jogadores e a validação das jogadas.
* **View (`_View.cpp/h`)**: Cuida da interface com o usuário, renderizando o tabuleiro, as peças disponíveis e os menus de interação no terminal.
* **Controller (`_Controller.cpp/h`)**: Orquestra a execução da partida, intermediando as ações do usuário (View) com as regras do jogo (Model).

## 🚀 Como Compilar e Executar

Abra o terminal na raiz do projeto e utilize um compilador C++ (como o `g++`):

```bash
# 1. Compilar os arquivos
g++ Dom_ALGH_Main.cpp Dom_ALGH_Model.cpp Dom_ALGH_View.cpp Dom_ALGH_Controller.cpp -o jogo_domino

# 2. Executar (Linux ou macOS)
./jogo_domino

# 2. Executar (Windows)
jogo_domino.exe
