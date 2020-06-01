# Classificador de Espécies de Passáros
Esse notebook é inspirado na primeira aula do curso da fast.ai Practical Deep Learning for Coders.
This notebook is inspired in the first class of fast.ai **Practical Deep Learning for Coders** course.

O objetivo deste projeto é constuir uma aplicação de machine learning que consiga classificar imagens de 9 diferentes espécies brasileiras. Para isso utilizei a biblioteca fast.ai e a técnica transfer-learning.

# Scraping dos Dados

Eu utilizei o script [**googliser**](https://github.com/teracow/googliser) para fazer o download das imagens dos passáros e construir meu banco de imagens.

# Modelos
Para este projeto eu utilizei uma rede pré-treinada Resnet34 e realizei algumas etapas de fine-tunning para melhorar os resultados.

# Performance dos Modelos
- Default Resnet34: Acurácia = 92.06 % 
- Fine-Tuned Resnet34: Acurácia = 95.24 %

# Code and Resources Used

- Python Version: 3.7
- Packages: fast.ai
