# Notas de Atletas: Cálculo de Média Olímpica 🏅

![Linguagem](https://img.shields.io/badge/Linguagem-JavaScript-F7DF1E?style=for-the-badge&logo=javascript)
![Status](https://img.shields.io/badge/Status-Concluído-4CAF50?style=for-the-badge)

> Projeto para calcular a média de notas de atletas em uma competição de ginástica, descartando a maior e a menor nota, conforme a regra da média olímpica.

---

### 📋 Índice

*   [🎯 Sobre o Projeto](#-sobre-o-projeto)
*   [🤸 Regra de Avaliação](#-regra-de-avaliação)
*   [🛠️ Tecnologias Utilizadas](#-tecnologias-utilizadas)
*   [🚀 Como Executar](#-como-executar)
*   [🧠 Aprendizados](#-aprendizados)
*   [🖥️ Saída no Console](#-saída-no-console)
*   [👨‍💻 Autor](#-autor)

---

### 🎯 Sobre o Projeto

Este projeto consiste em uma aplicação em JavaScript puro que processa uma lista de atletas e suas notas. O principal desafio foi implementar a lógica de cálculo da **média olímpica**, que desconsidera a nota mais alta e a mais baixa antes de calcular a média final das três notas restantes.

### 🤸 Regra de Avaliação

A competição segue uma regra de pontuação específica baseada em cinco notas de jurados:

> -   **Total de Notas:** Cada atleta recebe 5 notas.
> -   **Filtragem:** A maior e a menor nota são eliminadas.
> -   **Cálculo da Média:** A média final é calculada usando apenas as três notas centrais restantes.

### 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

*   **JavaScript:** Linguagem principal para toda a lógica de processamento e cálculo de dados.
*   **Node.js:** Ambiente para execução do script.

### 🚀 Como Executar

1.  Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em sua máquina.
2.  Clone o repositório ou baixe os arquivos.
3.  Abra o terminal na pasta do projeto e execute o seguinte comando:

```bash
node notas-atletas.js
```

### 🧠 Aprendizados

Este projeto foi fundamental para solidificar conceitos essenciais de manipulação de dados em JavaScript:

*   **Manipulação Avançada de Arrays:**
    *   **Iteração (`for...of`):** Para percorrer eficientemente um array de objetos.
    *   **Cópia de Arrays (`.slice()`):** Para criar uma cópia do array de notas, preservando o array original.
    *   **Ordenação (`.sort()`):** Para ordenar valores numéricos corretamente com uma função de comparação `(a, b) => a - b`.
    *   **Seleção (`.slice(1, 4)`):** Para extrair as três notas centrais após a ordenação.
*   **Funções e Lógica de Programação:**
    *   **Modularização:** Encapsulamento de toda a lógica na função `processarNotasAtletas`.
    *   **Acumulação de Valores:** Uso do `.forEach()` para somar as notas válidas.
*   **Estruturas de Dados:**
    *   Prática na manipulação de um array de objetos, acessando propriedades aninhadas como `atleta.nome` e `atleta.notas`.

### 🖥️ Saída no Console

A execução do script gera a seguinte saída:

```
    Atleta: Cesar Abascal
    Notas Obtidas: 10,9.34,8.42,10,7.88
    Média Válida: 9.253333333333334

    Atleta: Fernando Puntel
    Notas Obtidas: 8,10,10,7,9.33
    Média Válida: 9.11

    Atleta: Daiane Jelinsky
    Notas Obtidas: 7,10,9.5,9.5,8
    Média Válida: 9

    Atleta: Bruno Castro
    Notas Obtidas: 10,10,10,9,9.5
    Média Válida: 9.833333333333334
```
---
### 👨‍💻 Autor
Desenvolvido por **joaomaxdev** como parte do programa **DEVstart - JavaScript Frontend**.
