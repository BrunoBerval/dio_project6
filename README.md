# dio_project6
Sistema de Recomendação por Imagens Digitais

# Sistema de Recomendação por Imagens Digitais

Este projeto utiliza aprendizado profundo para buscar imagens semelhantes dentro de categorias específicas de produtos de um e-commerce. Ele utiliza o modelo VGG16, pré-treinado no conjunto de dados ImageNet, para extrair características profundas das imagens e calcular a similaridade entre elas usando a distância euclidiana, para assim poder recomendar produtos de acordo com a prefência do usuário.

## Funcionalidade

1. **Carregar o modelo VGG16** sem a camada de classificação (topo) para extrair características das imagens.
2. **Pré-processar a imagem** de entrada, redimensionando-a para 224x224 pixels e normalizando-a para que se torne compatível com o modelo.
3. **Extrair as características profundas** da imagem de entrada.
4. **Indexar as imagens de uma categoria específica** do e-commerce e calcular suas características.
5. **Calcular a similaridade** entre a imagem de entrada e as imagens indexadas usando a distância euclidiana.
6. **Retornar as N imagens mais semelhantes** da categoria, com base na distância euclidiana calculada.

**link para o dataset:** https://drive.google.com/drive/folders/17Lj60b9C5nxJVTnqG0VjOb-E-mXC9b_A?usp=sharing

----------------------------------------------------------------------------------------------------------------------
# Digital Image Recommendation System

This project uses deep learning to search for similar images within specific product categories of an e-commerce platform. It employs the pre-trained VGG16 model, trained on the ImageNet dataset, to extract deep features from images and calculate similarity between them using Euclidean distance, in order to recommend products based on user preferences.

## Functionality

1. **Load the VGG16 model** without the classification layer (top) to extract features from the images.
2. **Pre-process the input image**, resizing it to 224x224 pixels and normalizing it to make it compatible with the model.
3. **Extract deep features** from the input image.
4. **Index images from a specific category** in the e-commerce platform and calculate their features.
5. **Calculate the similarity** between the input image and the indexed images using Euclidean distance.
6. **Return the top N most similar images** from the category, based on the calculated Euclidean distance.

**Link to the dataset:** [https://drive.google.com/drive/folders/17Lj60b9C5nxJVTnqG0VjOb-E-mXC9b_A?usp=sharing](https://drive.google.com/drive/folders/17Lj60b9C5nxJVTnqG0VjOb-E-mXC9b_A?usp=sharing)
