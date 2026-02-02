# Reconhecimento e Contagem de Pessoas em Vídeo com YOLOv8

Este projeto realiza **detecção, identificação e contagem de pessoas em vídeos**
utilizando o modelo **YOLOv8**, aplicado sobre frames de vídeo de forma automática.
O sistema identifica apenas a classe *pessoa* e gera um novo vídeo anotado com
caixas delimitadoras e contagem dos indivíduos detectados.

---

## Objetivo

O objetivo do projeto é aplicar técnicas de **Visão Computacional e Deep Learning**
para detectar e contar pessoas em vídeos, explorando modelos de detecção de objetos
em tempo real e ferramentas modernas de anotação visual.

Esse trabalho foi feito como projeto da seleção do laboratório de analise de imagem do IFCE - Campus Fortaleza 

---

## Metodologia

O pipeline do projeto segue os seguintes passos:

1. Carregamento do vídeo de entrada
2. Extração de frames do vídeo
3. Detecção de objetos utilizando **YOLOv8**
4. Filtragem da classe **0 (Pessoa)**
5. Definição de uma área de interesse (ROI) para contagem
6. Anotação dos frames com bounding boxes
7. Geração de um vídeo final com as marcações

---

## Funcionalidades

- Detecção de pessoas em vídeos
- Filtragem de classes (apenas humanos)
- Contagem de pessoas dentro de uma região definida
- Geração de vídeo anotado como saída
- Visualização do vídeo diretamente no notebook
- Compatível com **Google Colab** e execução local

---

## Tecnologias Utilizadas

- Python
- PyTorch
- YOLOv8 (Ultralytics)
- Supervision
- NumPy
- OpenCV (indiretamente via bibliotecas)
- Google Colab

---
