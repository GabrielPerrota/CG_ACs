Repositório/Código público:

Exemplo OpenGL: LearnOpenGL - Getting Started

Trecho básico de renderização:

```cpp
// Inicialização OpenGL
glClear(GL_COLOR_BUFFER_BIT | GL_DEPTH_BUFFER_BIT);
// Renderização de cubo
cube.draw();
// Renderização de esfera
sphere.draw();

Execução:

Abre a janela OpenGL e renderiza os objetos com iluminação.

Mostra como coordenadas, cores e luz interagem para gerar a imagem.