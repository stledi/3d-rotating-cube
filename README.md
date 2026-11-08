# 3D Rotating Cube in Modern OpenGL

Um projeto minimalista em C++20 que renderiza e rotaciona um cubo 3D texturizado em tempo real utilizando **Modern OpenGL**, **GLEW**, **GLFW** e **GLM**.

Este projeto foi desenvolvido com foco no aprendizado de computação gráfica de baixo nível e na construção de um pipeline de renderização manual (Shaders, VBOs, VAOs, EBOs e matrizes de transformação MVP).

Uma prova da execução pode ser encontrada no próprio repositório entitulada como execucao.mp4

\---

## 📌 Sobre o Projeto

O objetivo principal deste repositório é servir como uma base sólida e um exemplo prático de visualização 3D sem o uso de engines prontas.

### Principais recursos:

* Renderização de malha 3D (Cubo) com índices (EBO/IBO).
* Transformações de matriz em 3D: **Model**, **View** e **Projection** (MVP) usando **GLM**.
* Pipeline com Shaders customizados em GLSL (Vertex e Fragment Shaders).
* Loop de renderização com cálculo de rotação contínua ao longo do tempo.
* Gerenciamento de contexto e janela via **GLFW** e carregamento de extensões via **GLEW**.

\---

## 🎓 Referências e Inspirações

Este projeto foi construído estudando e se inspirando nos seguintes recursos da comunidade:

* [**LearnOpenGL**](https://learnopengl.com/) por Joey de Vries — Referência principal para conceitos de pipeline 3D, matrizes de transformação e GLSL.
* [**The Cherno - OpenGL Series**](https://www.youtube.com/playlist?list=PLlrATfBNZ98foTJPJ_Ev03o2vqubOKbl0) — Série de tutoriais fundamental para a estruturação de abstrações em C++ e entendimento do fluxo do OpenGL.

\---

## 🛠️ Requisitos de Ambiente

Para compilar e executar o projeto no Windows (64-bit), você precisará do conjunto de ferramentas MinGW-w64:

* **MinGW-w64** (Recomendado via [WinLibs](https://winlibs.com/#download-release))

\---

## 🚀 Como Executar

Clone o repositório e execute run.bat via terminal:

```bash
git clone \[https://github.com/Gustavo-Stedile/minimal-opengl-glew-glm-environment.git](https://github.com/Gustavo-Stedile/minimal-opengl-glew-glm-environment.git)
cd minimal-opengl-glew-glm-environment
.\\run.bat

