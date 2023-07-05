# Pré-requisitos para jogar o Pac-mon

Vamos instalar os pacotes necessários para o **Pac-mon em menos de 5 minutos**.

## Instalando o Python e o pip

Comece **instalando o Python3 no seu sistema operacional**.

### Linux

- [Python3](https://www.python.org/downloads/) versão 3.9 ou acima:
  ```bash
  sudo apt install python3
  ```
- Pip:
  ```bash
  sudo apt install python3-pip
  ```

### Windows

- Acesse o site do [Python3](https://www.python.org/downloads/) oficial, baixe o instalador do python 3.x para Windows.
- Execute o instalador baixado e siga as instruções na tela.
- Marque a opção "Adicionar Python 3.x ao PATH" durante a instalação.
- Para instalar o pip, abra o cmd ou powershell e execute o comando:
  ```bash
  python -m ensurepip --upgrade
  ```

### Mac OS

- Abra o terminal e instale o Homebrew:
  ```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
- Agora instale o Python:
  ```bash
  brew install python3
  ```
- Por fim, instale o pip:
  ```bash
  sudo easy_install pip
  ```

## Instale o Tupy

A instalação do Tupy é necessária para a abertura do **Pac-mon**.

No seu terminal, execute o seguinte comando:

```bash
pip install git+https://github.com/rodrigorgs/tupy.git
```

### Tupy em ambiente virtual

Caso você não consiga fazer a instalação do Tupy via terminal, você pode instalar via um ambiente virtual criado pelo python. Para isso, execute esses comandos:

```python
python3 -m venv /caminho/para/o/diretorio/do/pac-mon/
```

Agora ative o ambiente virtual:

```python
source bin/activate
```

Por fim, tente instalar o Tupy novamente:

```bash
pip install git+https://github.com/rodrigorgs/tupy.git
```

# Vamos jogar Pac-mon

Para inicializar o Pac-mon, basta você executar o seguinte comando no terminal:

```bash
python3 /caminho/para/o/arquivo/main.py
```

- Após isso, basta apertar enter para iniciar sua gameplay, capturar todos pokemons antes que o tempo acabe e ser feliz!

## Descrição do projeto:

- Pokeman é um jogo inspirado no clássico Pacman, mas com elementos do universo Pokémon. O jogador controla uma pokebola através das setas do teclado, e sua missão é caçar todos os pokemons no labirinto. Quando um pokemon é capturado, ele evolui e aparece em um local aleatório do mapa. O objetivo é capturar todos os pokemons e suas respectivas formas evoluídas para encerrar a partida.

## Orientações sobre como usar o programa:

- O jogador controla a pokebola usando as setas do teclado (cima, baixo, esquerda, direita) para movê-la pelo labirinto. O jogo começa com alguns pokemons espalhados pelo mapa. O jogador deve guiar a pokebola para capturá-los. Ao capturar um pokemon, ele evolui para sua forma seguinte e reaparece em outro lugar aleatório do labirinto. O jogador deve continuar a busca até capturar todos os pokemons e suas formas evoluídas para vencer o jogo.

## Integrantes da equipe:

### Felipe Sanches:

- Descrição da contribuição:
  Responsável pelo mapa e criação das barreiras e restrições de rota no labirinto.
  - Nota de contribuição: 5/5

### Virgínia Lucia:

- Descrição da contribuição:
  Encarregada de criar os pokemons e suas formas evoluídas, incluindo suas animações e interações com o jogador.
  - Nota de contribuição: 5/5

### Eduardo Vasconcelos:

- Descrição da contribuição:
  Responsável pela documentação, lógica de evolução dos pokemons, gerenciamento da dinâmica do jogo e implementação de funcionalidades adicionais.
  - Nota de contribuição: 5/5

### Ryan Reis:

- Descrição da contribuição:
  Encarregado da programação da pokebola e sua interação com os pokemons e o ambiente do jogo.
  - Nota de contribuição: 5/5

## Outras informações relevantes:

Apesar de ter definido partes específicas para cada componente a princípio, a equipe trabalhou de forma colaborativa, realizando reuniões diárias pelo Discord e compartilhando a tela para desenvolverem as diferentes partes do jogo juntos. Todos os integrantes contribuíram ativamente para o projeto. O jogo foi desenvolvido com base nas habilidades individuais de cada membro, mas todos estiveram envolvidos em todas as etapas, tornando o processo mais eficiente e integrado. O nome "Pacmon" é uma combinação dos nomes "Pokemon" e "Pacman", refletindo a natureza do jogo, que mistura elementos dessas duas franquias populares.
