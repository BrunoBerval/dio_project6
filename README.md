# dio_project6
Sistema de Recomendação por Imagens Digitais

# E-commerce Image Similarity Search

Este projeto utiliza aprendizado profundo para buscar imagens semelhantes dentro de uma categoria específica de um e-commerce. Ele utiliza o modelo VGG16, pré-treinado no conjunto de dados ImageNet, para extrair características profundas das imagens e calcular a similaridade entre elas usando a distância euclidiana.

## Funcionalidade

1. **Carregar o modelo VGG16** sem a camada de classificação (topo) para extrair características das imagens.
2. **Pré-processar a imagem** de entrada, redimensionando-a para 224x224 pixels e normalizando-a para que se torne compatível com o modelo.
3. **Extrair as características profundas** da imagem de entrada.
4. **Indexar as imagens de uma categoria específica** do e-commerce e calcular suas características.
5. **Calcular a similaridade** entre a imagem de entrada e as imagens indexadas usando a distância euclidiana.
6. **Retornar as N imagens mais semelhantes** da categoria, com base na distância euclidiana calculada.
