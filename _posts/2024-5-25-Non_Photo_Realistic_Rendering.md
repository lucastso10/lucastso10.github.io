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
