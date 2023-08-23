# Markdown Links

## Índice

* [1. Prefácio](#1-prefácio)
* [2. Resumo do projeto](#2-resumo-do-projeto)
* [3. Guia de instalação e uso](#3-guia-de-instalação-e-uso)
* [4. Tecnologias utilizadas](#4-tecnologias-utilizadas)
* [5. Desenvolvedora](#5-desenvolvedora)

***

## 1. Prefácio

[Markdown](https://pt.wikipedia.org/wiki/Markdown) é uma linguagem de marcação
muito popular entre os programadores. É usada em muitas plataformas que
manipulam texto (GitHub, fórum, blogs e etc) e é muito comum encontrar arquivos
com este formato em qualquer repositório (começando pelo tradicional
`README.md`).

Os arquivos `Markdown` normalmente contém _links_ que podem estar
quebrados, ou que já não são válidos, prejudicando muito o valor da
informação que está ali.

Uma comunidade open source nos propôs criar uma ferramenta, usando
[Node.js](https://nodejs.org/), que leia e analise arquivos no formato
`Markdown`, para verificar os arquivos que contenham links e mostrar algumas
estatísticas.

## 2. Resumo do projeto

Neste projeto, foi criada uma ferramenta de linha de comando (CLI) assim como
a sua própria biblioteca (library) em Javascript.

## 3. Guia de instalação e uso
### 3.1 Instalação
1. Abra o terminal
2. Execute o seguinte comando para instalar o MD-Links globalmente:
```bash
npm install -g fernandasouza-md-links
```

### 3.2 Uso

**1. Para extrair links de um arquivo Markdown:**
```bash
mdLinks caminho/do/arquivo.md
```
**Exemplo de resultado:** 

![Extrair links](</src/img/arquivo.png>)

**2. Para extrair e verificar o status HTTP dos links:**

```bash
mdLinks caminho/do/arquivo.md --validate
``` 
**Exemplo de resultado:** 

![Links validate](<src/img/validate.png>)

**3. Para obter estatísticas sobre os links:**

```bash
mdLinks caminho/do/arquivo.md --stats
``` 
**Exemplo de resultado:** 

![Link stats](<src/img/stats.png>)

**4. Para obter estatísticas e validar os links:**

```bash
mdLinks caminho/do/arquivo.md --stats --validate
``` 
**Exemplo de resultado:** 

![Link validate and stats](<src/img/validade-stats.png>)

## 4. Tecnologias utilizadas
![JAVASCRIPT ICON](https://skillicons.dev/icons?i=js,nodejs,git,vscode)

## 5. Desenvolvedora

### Fernanda Araújo de Souza

[![LINKEDIN ICON](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/fernandaasouza/)
[![GITHUB ICON](https://skillicons.dev/icons?i=github)](https://github.com/fernanda-asouza)