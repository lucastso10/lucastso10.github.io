---
layout: post
title: Semana 2 - Se aprofundando
---

Nessa semana os alunos foram orientados a realizar uma pesquisa sobre diferente áreas da computação visual.

# Computação Gráfica 

# Processamento de imagens
## Segmentação por crescimento de região

A segmentação por crescimento de região é uma técnica de processamento de imagens onde os pixels são agrupados em regiões com base em critérios de similaridade. 

Ao invés de usar um valor global como na segmentação por limiar, o processo começa com um pixel semente e expande a região adicionando pixels vizinhos que atendem aos critérios de similaridade, como cor, intensidade ou textura. Essa abordagem é eficaz para objetos com características uniformes, como em imagens médicas ou detecção de objetos em cenas naturais.

O algoritmo continua iterativamente até que a região esteja completa ou não haja mais pixels que atendam aos critérios, proporcionando uma segmentação detalhada e precisa em casos onde objetos têm características similares.


Escolhemos a segmentação por crescimento de região por conta de sua aplicação nas análise de imagens de satélites, utilizado para o mapeamento terrestre por exemplo. Esse método segmenta diferentes tipos de cobertura terrestre, como florestas, corpos de água e áreas urbanas.

[Fonte](https://www.dpi.inpe.br/spring/portugues/tutorial/segmentacao.html)

# Visão Computacional
