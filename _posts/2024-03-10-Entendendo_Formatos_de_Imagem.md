---
layout: post
title: Semana 3 - Entendendo Formatos de Imagem
---

Nessa semana, vimos que os processos de amostragem e quantização são realizados para converter dados contínuos (capturados por sensores de aquisição de imagens) em dados discretos, resultando na geração de imagens digitais. Para aprofundar nossos estudos decidimos procurar sobre como as imagens do tipo .png são armazenadas, e qual tipo de informações extras ela carrega.

# Estrutura

A estrutura de uma imagem PNG pode ser observada na imagem abaixo:

![PNGRGB_dissected](https://github.com/lucastso10/lucastso10.github.io/assets/84486266/e545537e-4bca-40a4-8239-4a850ac0bbdb)
*Fonte: [https://github.com/corkami/formats/blob/master/image/png.md](https://github.com/corkami/formats/blob/master/image/png.md)*

É possível observar que o arquivo começa com um Signature, que o identifica. Logo em seguida temos o Header com informações necessarias, logo em seguida temos a Data da imagem onde pode ser encontrado os valores dos pixels individuias, e por último o End, o final do arquivo.

### Header

O Header possui informações como o tamanho, filtros, cores e compressão que a imagem utiliza.

### Data

A secção Data no arquivo possui não só os valores individuais de cada pixel, mas támbem informações de como esses dados estão comprimido (zlib) 

Na parte 

# Autores
Lucas Teixeira Soares

Mateus Fernandes Castanharo
