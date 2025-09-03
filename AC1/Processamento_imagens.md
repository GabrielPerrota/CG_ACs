Repositório/Código público:

Exemplo OpenCV: OpenCV-Python Tutorials

Código exemplo:

```python

import cv2

img = cv2.imread('imagem.jpg', 0)
edges = cv2.Canny(img, 100, 200)
cv2.imshow('Edges', edges)
cv2.waitKey(0)
cv2.destroyAllWindows()

```

Execução:

Mostra a imagem original e a borda detectada.

Destaca como o processamento de imagens transforma dados visuais em informação útil.