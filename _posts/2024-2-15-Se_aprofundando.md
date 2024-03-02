---
layout: post
title: Semana 2 - Se aprofundando
---

Nessa semana os alunos foram orientados a realizar uma pesquisa sobre diferente áreas da computação visual.

# Computação Gráfica 

# Processamento de imagens
### Segmentação por crescimento de região

A segmentação por crescimento de região é uma técnica de processamento de imagens onde os pixels são agrupados em regiões com base em critérios de similaridade. 

Ao invés de usar um valor global como na segmentação por limiar, o processo começa com um pixel semente e expande a região adicionando pixels vizinhos que atendem aos critérios de similaridade, como cor, intensidade ou textura. Essa abordagem é eficaz para objetos com características uniformes, como em imagens médicas ou detecção de objetos em cenas naturais.

O algoritmo continua iterativamente até que a região esteja completa ou não haja mais pixels que atendam aos critérios, proporcionando uma segmentação detalhada e precisa em casos onde objetos têm características similares.


Escolhemos a segmentação por crescimento de região por conta de sua aplicação nas análise de imagens de satélites, utilizado para o mapeamento terrestre por exemplo. Esse método segmenta diferentes tipos de cobertura terrestre, como florestas, corpos de água e áreas urbanas.

[Fonte](https://www.dpi.inpe.br/spring/portugues/tutorial/segmentacao.html)

# Visão Computacional
### Rastreamento de Movimento

O rastreamento de movimento na visão computacional é a técnica de seguir e analisar o movimento de objetos ou pessoas em vídeos ou sequências de imagens. Essencial em muitas aplicações, desde análise de movimento humano em esportes até animação de personagens em jogos, seu objetivo é monitorar a trajetória e a posição dos objetos ao longo do tempo para extrair informações dinâmicas da cena.

Há diversas abordagens para o rastreamento de movimento, incluindo métodos baseados em modelos e em características visuais. Os métodos baseados em modelos usam modelos matemáticos para prever a posição futura dos objetos com base em seu movimento passado, enquanto os métodos baseados em características visuais identificam pontos de referência nos objetos e os acompanham ao longo do tempo.

Amplamente usado em aplicações como análise de movimento humano, segurança e monitoramento de tráfego, o rastreamento de movimento enfrenta desafios como oclusão e mudanças de iluminação. Pesquisas contínuas buscam aprimorar a precisão e a robustez desses sistemas em diferentes cenários e condições.


Escolhemos esse tema devido a familiaridade que temos por participarmos do Hackathon onde a ideia principal era o rastreamento de movimento dentro da Universidade Presbiteriana Mackenzie.

[Fonte](https://web.fe.up.pt/~rpinho/Introducao_jt.pdf)
