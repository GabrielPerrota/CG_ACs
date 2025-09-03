Repositório/Código público:

Exemplo Python + Matplotlib: Matplotlib Examples

Código exemplo:
```python
import matplotlib.pyplot as plt
from mpl_toolkits.mplot3d import Axes3D
import numpy as np

fig = plt.figure()
ax = fig.add_subplot(111, projection='3d')
x = np.random.rand(50)
y = np.random.rand(50)
z = np.random.rand(50)
ax.scatter(x, y, z)
plt.show()

```
Execução:

Gera um gráfico 3D interativo com dados aleatórios.

Permite análise visual rápida de padrões e distribuições.