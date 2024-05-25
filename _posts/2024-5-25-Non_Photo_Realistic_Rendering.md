---
layout: post
title: Semana 16 - Non Photo Realistic Rendering
---

Normalmente na área de computação visual, estamos sempre procurando algoritmos para alcançar cenários
cada vez mais proximos da realidade. Pórem, algumas vezes podemos querer tomar a liberdade artística
para fazermos algo que não é realistico, essas tecnicas são chamadas de NPR (Non Photo Realistic Rendering)
. Uma das técnicas mais utilizadas nesse ramo é o de *toon/cel shading*.

# Toon/cel shading

Toon shading, ou cel shading, é uma técnica de renderização usada para fazer imagens 3D parecerem com desenhos animados ou ilustrações feitas à mão,
proporcionando uma textura semelhante a papel, e recebe o nome de “cels” (celuloide) usados em animações 2D. 
Essa técnica simplifica a paleta de cores e utiliza bordas bem definidas para criar um visual estilizado e não fotorrealista, similar ao que é visto em quadrinhos e animações.

Esse técnica utiliza de processos como simplificação de cores, onde não as cores não mudam gradualmente e junto da quantização das cores, permite o estilo cartoonizado, e a demilitação de bordas, onde as bordas são realçadas para
passar a ideia de um desenho feito à mão. Durante o processo, o cálculo da iluminação é semelhante aos modelos tradicionais, contudo temos a quantização previa das cores, já para a demilitação de bordas,  pode ser feito através da 
inversão das normais da malha e renderização de uma silhueta ou usando técnicas de pós-processamento para detectar e realçar bordas.

Os métodos de Toon/Gourand/Phong Shading tem suas semelhanças, todas as três técnicas utilizam cálculos de iluminação para determinar a aparência final dos pixels, dependem das normais das superfícies para calcular a luz refletida
e todas são usadas para renderizar superfícies tridimensionais. Já para as diferenças temos, a iluminação para o toon shading é calculada em intervalos discretos, resultando em uma quantidade limitada de níveis de brilho, para Gourand, 
é calculada nos vértices dos polígonos. A cor resultante é então interpolada entre os vértices ao longo da superfície do polígono e na técnica de Phong, a iluminação é calculada para cada pixel, 
utilizando normais interpoladas de vértices. Outro quesito é a transição de cores, para a técnica Toon, as transições entre diferentes níveis de brilho são abruptas, criando um visual estilizado e gráfico, contudo, para as técnicas de
Gourand e Phong as transições de cor são extremamente suaves e realistas.

![image](https://github.com/lucastso10/lucastso10.github.io/assets/84486266/cdf7dc8f-d265-4945-89f1-88dbc31b211c)
*Image de comparação do shader Universal RP da Unity com o shader UniToon encontrado nesse link https://github.com/yoship1639/UniToon*
