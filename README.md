
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
