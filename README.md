# Gerador de Senhas — Programação Estruturada em Python

<p align="center">
  <img alt="Python 3" src="https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="Programação estruturada" src="https://img.shields.io/badge/Paradigma-Programação%20Estruturada-374151?style=flat-square" />
  <img alt="Projeto de estudos" src="https://img.shields.io/badge/Tipo-Projeto%20de%20Estudos-16A34A?style=flat-square" />
</p>

Projeto acadêmico desenvolvido em **Python** para exercitar o **paradigma de programação estruturada** por meio de um gerador de senhas. O objetivo é praticar lógica de programação, entradas de dados, condições, repetição e organização do código em funções.

## Objetivo

Construir uma aplicação que receba preferências do usuário e gere uma sequência de caracteres como senha, aplicando os fundamentos da programação estruturada em Python.

## Funcionalidades

- Solicitação de parâmetros para gerar uma senha.
- Geração e exibição de uma sequência de caracteres.
- Interação pelo terminal, com aplicação de estruturas condicionais e de repetição.

> **Antes de publicar:** confirme no código se há definição de comprimento, escolha de letras maiúsculas/minúsculas, números e símbolos, além de validação de entradas. Esses detalhes não foram verificados diretamente no repositório atual.

## Tecnologias e conceitos

| Tecnologia ou conceito | Aplicação |
| --- | --- |
| **Python 3** | Linguagem de programação |
| **Programação estruturada** | Organização do fluxo de execução |
| **Condições e laços** | Controle das escolhas e geração |
| **Funções** | Possível separação das responsabilidades do algoritmo |
| **Strings** | Manipulação dos caracteres da senha |

## Como executar

**Pré-requisito:** [Python 3](https://www.python.org/downloads/) instalado.

1. Clone o repositório e entre na pasta:

   ```bash
   git clone https://github.com/adolfo-araujo/Gerador-de-Senha-Paradigma-estruturado-.git
   cd Gerador-de-Senha-Paradigma-estruturado-
   ```

2. Localize o arquivo `.py` principal e execute-o:

   ```bash
   python nome-do-arquivo.py
   ```

   No Linux/macOS, se necessário, use `python3`.

   **Importante:** substitua `nome-do-arquivo.py` pelo nome verdadeiro do arquivo do projeto.

## Fluxo geral

```text
Início
  ↓
Ler as preferências do usuário
  ↓
Definir os caracteres disponíveis
  ↓
Gerar a senha
  ↓
Exibir o resultado
  ↓
Fim
```

## Nota de segurança

O projeto tem **finalidade educacional**. Sem conferir o mecanismo de aleatoriedade usado no código, não é possível afirmar que as senhas geradas são adequadas para uso real. Em Python, uma alternativa indicada para aplicações que exigem aleatoriedade criptograficamente segura é o módulo [`secrets`](https://docs.python.org/3/library/secrets.html).

## Aprendizados

O exercício reforça fundamentos de Python e programação estruturada, como variáveis, entrada e saída de dados, controle de fluxo e manipulação de strings.

## Autor

Desenvolvido por [João Adolfo](https://github.com/adolfo-araujo), estudante de Engenharia de Software.
