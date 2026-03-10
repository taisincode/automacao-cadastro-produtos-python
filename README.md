# Automação de Cadastro de Produtos com Python

Script de automação desenvolvido em Python para realizar login em um sistema web e cadastrar produtos automaticamente a partir de uma base de dados em CSV.

## Descrição

Este projeto automatiza um processo repetitivo de cadastro de produtos em um sistema online. A automação abre o navegador, acessa a página de login, realiza autenticação e utiliza uma tabela de produtos para preencher automaticamente os campos do formulário.

O objetivo do projeto é praticar automação de tarefas com Python e manipulação de dados com Pandas.

## Tecnologias Utilizadas

- Python
- PyAutoGUI
- Pandas
- Time

## Funcionalidades

- Abertura automática do navegador
- Acesso ao sistema web
- Login automatizado
- Leitura de base de dados em CSV
- Preenchimento automático de formulário
- Cadastro automático de múltiplos produtos
- Repetição do processo para toda a base de dados

## Estrutura do Projeto

```
├── Automacao.py
├── pegar_posicao.py
├── produtos.csv
└── README.md
```

## Como Funciona

O script executa as seguintes etapas:

1. Abre o navegador Edge  
2. Acessa a página do sistema  
3. Realiza login no sistema  
4. Importa a base de produtos do arquivo `produtos.csv`  
5. Preenche automaticamente os campos do formulário  
6. Envia o cadastro do produto  
7. Repete o processo até cadastrar todos os produtos da tabela  

## Pré-requisitos

Antes de executar o projeto, é necessário ter instalado:

- Python 3

Bibliotecas utilizadas:

```
pyautogui
pandas
```

## Instalação das dependências

Execute no terminal:

```
pip install pyautogui pandas
```

## Configuração necessária

Antes de executar o script, é necessário inserir suas credenciais de acesso no código.

No arquivo `Automacao.py`, localize a parte responsável pelo login e substitua pelos seus dados:

```python
pyautogui.write("seu_email")
pyautogui.press("tab")
pyautogui.write("sua_senha")
```

## Observações

Este script utiliza coordenadas fixas de clique na tela. Dependendo da resolução do monitor, posição da janela ou velocidade de carregamento da página, pode ser necessário ajustar os valores de `x` e `y` utilizados no código.

Durante a execução, evite utilizar o mouse ou teclado para não interferir na automação.

## Objetivo do Projeto

Este projeto foi desenvolvido com foco em aprendizado, explorando conceitos como:

- automação de tarefas com Python
- manipulação de dados com Pandas
- uso da biblioteca PyAutoGUI
- leitura de arquivos CSV
- repetição de processos automatizados

## Créditos

Exercício proposto no **Intensivão de Python da Hashtag Treinamentos**.  
O código foi desenvolvido e adaptado para fins de estudo e prática.



