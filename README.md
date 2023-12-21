# Tranformações Geométricas
Código para transformações geométricas em Python desenvolvido na disciplina de Computação Gráfica.

## Tranformações Geométricas

1. Translação
2. Escala
3. Rotação
4. Espelhamento

## Bibliotecas Necessárias
- Pillow (PIL)
- Numpy
- Math
- Matplotlib

## 🤔 Como Funciona o Código
Primeiramente, é carregada uma imagem de escolha do usuário na linha 99:
```
img = Image.open('image/gray.jpg')
```
Caso queira inserir outra imagem de sua escolha, é só simplesmente mudar o diretório da imagem

Ao executar o código, irão ser mostradas as opções no terminal de qual tipo de tranformação o usuário deseja reaizar na imagem.

![image](https://github.com/rodineves/Tranformacoes-Geometricas/assets/105732866/c92a4371-b567-4f91-b6ec-7c334b967aad)


Ao escolher a opção digitando o número rspectivo e clicando Enter, o processamento ocorre e a imagem pós-processada é salva na mesma pasta da imagem original. Porém, se for de sua escolha pode mudar os diretórios:
```
inverted_img.save('image/gatenho_invertido.jpg')
```
Acima é o exemplo de salvar a imagem negativa na pasta <i>image</i>, mas pode mudar em todas as opções de processamento.
Além disso, ao final da execução, a biblioteca matplotlib irá mostras entre a imagem original e a imagem com a tranformação aplicada

![image](https://github.com/rodineves/Tranformacoes-Geometricas/assets/105732866/f6f7c23c-7fa2-4cbc-9c70-85138784a21b) Exemplo ao escolher espelhamento vertical.
