Notas de Atletas: Cálculo de Média Olímpica 🏅

[JavaScript Badge]

🌟 Resumo do Projeto

Este projeto consiste em uma aplicação JavaScript pura desenvolvida para
calcular a média de notas de atletas de uma competição de ginástica
artística. O desafio principal foi implementar a regra de avaliação que
desconsidera a nota mais alta e a mais baixa antes de calcular a média
final.

🤸 Regra de Avaliação

A competição segue uma regra de pontuação específica baseada em cinco
notas de jurados:

-   Total de Notas: Cada atleta recebe 5 notas (de 1 a 10)
-   Filtragem: A maior e a menor nota são eliminadas
-   Cálculo da Média: A média final é calculada usando apenas as três
    notas centrais restantes

🛠️ Tecnologias Utilizadas

  -----------------------------------------------------------------------
  Tecnologia                          Descrição
  ----------------------------------- -----------------------------------
  JavaScript                          Linguagem principal para toda a
                                      lógica de processamento e cálculo
                                      de dados

  -----------------------------------------------------------------------

🧠 O que Aprendi (Foco DEVstart)

Este projeto foi fundamental para solidificar conceitos essenciais de
manipulação de dados em JavaScript, importantes para o desenvolvimento
Frontend:

1. Manipulação Avançada de Arrays

-   Iteração (for...of): Aprendi a percorrer eficientemente um array de
    objetos complexos (a lista de atletas)
-   Cópia de Arrays (.slice()): Usei Array.prototype.slice() para criar
    uma cópia rasa do array de notas, garantindo a integridade dos dados
    de exibição
-   Ordenação Personalizada (.sort()): Utilizei o .sort((a, b) => a - b)
    com função de comparação para ordenação correta de valores numéricos
-   Filtragem de Subconjuntos (.slice(1, 4)): Apliquei o método .slice()
    com índices específicos para isolar as três notas centrais após a
    ordenação

2. Funções e Lógica Condicional

-   Modularização: Criei uma função principal (processarNotasAtletas)
    para encapsular toda a lógica de cálculo
-   Acumulação de Valores (.forEach()): Usei o .forEach() para iterar
    sobre as notas válidas e somar seus valores

3. Estruturas de Dados

-   Trabalho com Objetos e Arrays Aninhados: Pratiquei a navegação e
    extração de dados de uma estrutura Array de Objetos, acessando
    propriedades aninhadas como atleta.nome e atleta.notas

⚙️ Como o Código Funciona

O fluxo lógico para calcular a média de cada atleta é o seguinte:

1.  Iteração: Percorre a lista de atletas
2.  Cópia e Ordenação: Cria uma cópia das notas e as ordena
3.  Seleção: Usa .slice(1, 4) para obter as 3 notas centrais (índices 1,
    2 e 3)
4.  Soma: Soma as notas centrais
5.  Média: Divide a soma por 3
6.  Saída: Exibe o resultado no console

🖥️ Saída (Resultado no Console)

O projeto processa os dados de entrada e gera a seguinte saída no
console:

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

------------------------------------------------------------------------

👨‍💻 Desenvolvido por joaomaxdev
Projeto desenvolvido como parte do programa DEVstart - JavaScript
Frontend
