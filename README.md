# Processamento de Imagens com Threads

Este projeto consiste em desenvolver um programa em uma linguagem de programação que utilize threads para realizar o processamento de imagens digitais de acordo com o algoritmo de detecção de bordas apresentado no enunciado. O programa terá uma thread principal responsável por abrir e representar a imagem em nível de cinza, bem como criar duas threads filhas para calcular as imagens de bordas Gx e Gy. Após a conclusão das tarefas das threads filhas, a thread principal calculará a imagem de saída G a partir das imagens Gx e Gy. A sincronização entre as threads será feita usando a função "join" da biblioteca de threads utilizada.

## Linguagem de Programação

A escolha da linguagem de programação para este projeto é crucial. Uma linguagem que ofereça suporte a threads e manipulação de imagens é essencial. Algumas opções adequadas incluem C/C++, Python (com a biblioteca OpenCV), Java, entre outras. Neste exemplo, usaremos Python com a biblioteca OpenCV devido à sua facilidade de uso e recursos poderosos de processamento de imagens.

## Desenvolvedores

 - [Emanoel Batista](https://github.com/EmanoelBatista)
 - [Yan Tavares](https://github.com/yantvrs)

