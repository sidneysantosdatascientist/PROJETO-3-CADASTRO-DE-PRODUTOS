# Automação de Cadastro de Produtos com Python

Este repositório contém um script em Python que automatiza o processo de cadastro de produtos em um sistema utilizando as bibliotecas `openpyxl`, `pyperclip`, e `pyautogui`. O script lê os dados de um arquivo Excel (`produtos_ficticios.xlsx`) e preenche automaticamente os campos no sistema, utilizando coordenadas da tela e simulação de cliques e atalhos de teclado.

## Funcionalidades

- **Leitura de Dados do Excel**: Utiliza a biblioteca `openpyxl` para ler informações de produtos, incluindo nome, descrição, categoria, código, preço, entre outros.
- **Automação de Interação com Interface Gráfica**: Utiliza `pyautogui` para simular cliques e digitação nos campos do sistema.
- **Copiar e Colar**: Utiliza `pyperclip` para copiar os valores do Excel e colá-los nos campos corretos do sistema.
- **Cadastro Iterativo**: Realiza o cadastro de múltiplos produtos em sequência, com validações e interações conforme necessário.

## Pré-requisitos

Certifique-se de que você possui os seguintes itens instalados antes de executar o script:

1. Python 3.6 ou superior.
2. As bibliotecas Python utilizadas no script:
   - `openpyxl`: Para leitura e manipulação de arquivos Excel.
   - `pyperclip`: Para copiar e colar informações.
   - `pyautogui`: Para simular interações com a interface gráfica.

Você pode instalar as dependências utilizando o comando:

```bash
pip install openpyxl pyperclip pyautogui
