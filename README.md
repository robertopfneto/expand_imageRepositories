//PT-BR
# Gerador de Imagens Aumentadas com Pergunta de Processamento

Este script permite aplicar uma série de transformações de aumento de dados em uma imagem. Para cada tipo de transformação, o usuário é questionado se deseja aplicá-la ou não. O script salva as imagens processadas em uma pasta de saída específica.

## Funcionalidades

- Espelhamento Horizontal
- Espelhamento Vertical
- Rotação Aleatória
- Corte Aleatório
- Ruído Gaussiano
- Alteração de Brilho
- Escala (Redimensionamento)
- Shear (Inclinação)

## Como Usar

1. **Pré-requisitos**: Certifique-se de ter as bibliotecas `numpy`, `Pillow` e `imgaug` instaladas no seu ambiente Python. Você pode instalá-las com o comando:

   ```bash
   pip install numpy pillow imgaug
   ```

2. **Execução**: Para executar o script, basta rodar o `main.py`:

   ```bash
   python main.py
   ```


//EN-US

# Augmented Image Generator with Processing Question

This script allows you to apply a series of data augmentation transformations to an image. For each type of transformation, the user is asked whether they want to apply it or not. The script saves the processed images to a specific output folder.

## Features

- Horizontal Mirroring
- Vertical Mirroring
- Random Rotation
- Random Cut
- Gaussian noise
- Brightness Change
- Scale (Resizing)
- Shear

## How to Use

1. **Prerequisites**: Make sure you have the `numpy`, `Pillow` and `imgaug` libraries installed in your Python environment. You can install them with the command:

   ```bash
   pip install numpy pillow imgaug
   ```

2. **Execution**: To execute the script, simply run `main.py`:

   ```bash
   python main.py
   ```
