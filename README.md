# Segmentação de Tumor no Fígado

Este repositório contém um notebook para segmentação de tumores no fígado a partir de imagens médicas, utilizando técnicas de deep learning.

Dataset Utilizado

Task03_Liver do Medical Segmentation Decathlon

Imagens no formato NIfTI (.nii)

Técnicas Utilizadas

Pré-processamento: Utilização da biblioteca Nibabel para carregar imagens médicas e NumPy para manipulação dos dados.

Visualização: Uso de Matplotlib para exibir imagens segmentadas.

Modelo de Segmentação: Implementa um modelo baseado em deep learning (possivelmente U-Net ou variante).

Treinamento: Implementação de um processo de treinamento utilizando métricas de avaliação.

Resultados Obtidos

Métricas Avaliadas:

Dice Score

IoU (Intersection over Union)

Os resultados mostraram que o modelo alcançou um desempenho satisfatório na segmentação de tumores no fígado, com métricas indicando boa sobreposição entre previsões e regiões segmentadas.

Licença

Este projeto está sob a licença MIT.
