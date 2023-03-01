# Repósitorio destinado para as implementações dos algoritmos do Trabalho de Conclusão de Curso apresentado ao Curso de Graduação em Ciência da Computação do Campus Quixadá da Universidade Federal do Ceará

## Titulo do TCC: ALGORITMOS PARA O PROBLEMA DO NÚMERO DE GRUNDY

## Resumo <a name = "about"></a>

No presente trabalho, estudamos o Problema do Número de Grundy que consiste em determinar a maior quantidades de cores que o Algoritmo Guloso de Coloração consegue atribuir a um grafo. Este algoritmo tem o seguinte princípio geral: receber, um a um, os vértices do grafo a ser colorido, atribuindo sempre a menor cor possível a este vértice. O maior número de cores utilizados pelo Algoritmo Guloso de Coloração é chamado de número de Grundy ou número cromático guloso do grafo. Sabe-se que determinar o número de Grundy de um grafo qualquer pertence à classe NP-completo. O objetivo deste trabalho foi propor novas soluções exatas para o Problema do Número de Grundy. Neste trabalho, foram propostos um limite inferior e um superior, ambos baseados em heurísticas gulosas. Com relação às soluções exatas, foram propostas um algoritmo de Programação Dinâmica, um algoritmo Branch and Bound e três formulações de Programação Linear Inteira. Foram geradas instâncias aleatórias e da classe Stacked Book, no qual foram realizados diversos testes computacionais. Os resultados computacionais evidenciaram que nas instâncias aleatórias algoritmo proposto BBG supera o algoritmo PBG em relação à qualidade das soluções retornadas. Em instâncias de densidade média, a formulação F_DELTA conseguiu encontrar o resultado mais rápido que os demais algoritmos, enquanto que nas classes de densidade alta, a formulação F_ST F se mostrou mais eficiente. Nas instâncias da classe Stacked Book, a formulação F_PROD proposta se mostrou mais eficiente eficiente em todos os testes que os demais algoritmos propostos.

## Linguagem de Programação utilizada

<!-- <ul>
    <li>Python</li>
</ul> -->
<div class="center">
    <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white">
</div>

## Pacotes Python utilizados

<ul>
    <li>Networkx</li>
    <li>Google Ortools</li>
</ul>

## Algoritmos desenvolvidos

<ul>
    <li>Limite Inferior - LB-DEG</li>
    <li>Limite Superior - Stair Factor</li>
    <li>Algoritmo de Programação Dinâmica - PDG</li>
    <li>Algoritmo Branch and Bound - BBG</li>
    <li>Formulação de Programação Linear Inteira - F_DELTA</li>
    <li>Formulação de Programação Linear Inteira - F_STF</li>
    <li>Formulação de Programação Linear Inteira - F_PROD</li>
</ul>
