# Desafio_Imersao_Alura03
# Jupyter Notebook para Geração de Histórias Infantis com Google Generative AI

Este documento descreve um Jupyter Notebook que utiliza a biblioteca Google Generative AI para criar histórias infantis interativas. Este notebook é otimizado para execução no Google Colab e é composto por células de markdown e células de código Python.

## Metadados

- `nbformat` e `nbformat_minor`: Indicam a versão do formato do notebook.
- `metadata`: Contém configurações específicas para execução no Google Colab, informações sobre o kernel Python usado e dados sobre a linguagem de programação.

## Células

### Célula de Markdown

- Contém um link que permite abrir o notebook diretamente no Google Colab.

### Célula de Código (Importações Iniciais)

- Importa bibliotecas necessárias para a geração de conteúdo usando o modelo de IA da Google, geração de números aleatórios e funções para exibir resultados em Markdown.

### Célula de Código (Configuração da API)

- Configura a API do Google Generative AI com uma chave de API obtida dos dados do usuário no Colab.

### Célula de Código (Configurações do Modelo)

- Define as configurações para a geração de conteúdo pelo modelo `gemini-1.0-pro`, incluindo ajustes de 'temperatura' e configurações de segurança para filtragem de conteúdo sensível.

### Célula de Código (Funções de Geração de Conteúdo)

- Define a função `generate_story` que cria histórias baseadas em tema, personagem e elemento escolhidos pelo usuário.
- A função `main` interage com o usuário, coleta suas escolhas e gera uma história, que é formatada e exibida em Markdown.

## Funcionalidade

O programa solicita ao usuário que escolha um tema, personagem e elemento mágico para a história. Utiliza essas informações para gerar um conteúdo personalizado, criado pelo modelo de IA com base em um prompt fornecido. As histórias são exibidas utilizando formatação Markdown para uma apresentação visual amigável.
