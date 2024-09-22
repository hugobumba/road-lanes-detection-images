# Detecção de Linhas em Imagem Estática

Este projeto utiliza a técnica de Hough Transform para detectar linhas de pista em uma imagem estática. O código faz uso da biblioteca OpenCV e aplica várias técnicas de processamento de imagem, como detecção de bordas e seleção de região de interesse.

## Requisitos

- Python 3.x
- OpenCV
- NumPy

## Instalação

Para instalar as dependências, execute:

```bash
pip install opencv-python numpy
```

## Uso

1. Coloque uma imagem no mesmo diretório do script.
2. Execute o script:

```bash
python lane_detection_image.py
```

3. O programa abrirá uma janela exibindo a imagem com as linhas de pista detectadas.

## Funcionamento

- A imagem é lida e pré-processada com técnicas de conversão para escala de cinza e suavização.
- A detecção de bordas é aplicada usando o algoritmo de Canny.
- A transformação de Hough é usada para detectar as linhas de pista.
- As linhas detectadas são desenhadas sobre a imagem original.