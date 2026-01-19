# Xocopoli v2 🧊

**Xocopoli v2** es una potente herramienta de modelado 3D basada en la web, construida con **React**, **TypeScript** y **Three.js**. Permite a los usuarios crear, editar y manipular geometría 3D directamente en el navegador con una interfaz intuitiva y herramientas de nivel profesional.

🔗 **[Demo Pública](https://unreal-virgilio.github.io/xocopoli-v2/)**

![Menu de la aplicación](Menu.gif)

---

## ✨ Características Principales

### 🎯 Modos de Selección
Xocopoli v2 ofrece un control granular sobre tu geometría.

| Modo | Descripción | Previsualización |
|------|-------------|------------------|
| **Vertex** | Selecciona y manipula vértices individuales para un control preciso. | ![Vertex Selection](vertex.gif) |
| **Edge** | Trabaja con las aristas de tu modelo. | ![Edge Selection](edge.gif) |
| **Face** | Selecciona polígonos o caras completas. | ![Face Selection](face.gif) |
| **Object** | Manipula objetos completos en la escena. | ![Object Selection](object.gif) |
| **Multi** | Selección versátil adaptada a tus necesidades. | ![Multi Selection](multi.gif) |

---

### 🛠️ Herramientas de Modelado
Un set completo de operaciones para dar vida a tus ideas.

#### Extrusión e Inset
*   **Extrude**: Crea nueva geometría a partir de caras o aristas existentes.
*   **Inset**: Crea nuevas caras dentro de las seleccionadas.

![Extrude Tool](extrude.gif) ![Inset Tool](inset.gif)

#### Cortes y Subdivisiones
*   **Loop Cut**: Añade bucles de aristas para refinar la topología.
*   **Knife**: Corta geometría libremente dibujando sobre las caras.
*   **Subdivide**: Aumenta la resolución de tu malla suavizando o dividiendo caras.

![Loop Cut](loop%20cut.gif) ![Knife Tool](knife.gif) ![Subdivide](subdivide.gif)

#### Creación de Geometría
*   **Make Face**: Crea caras rellenando espacios entre vértices seleccionados.

![Make Face](make%20face.gif) ![Make Face Edge](make%20face%20edge.gif)

#### Simetría
*   **Symmetry**: Refleja tu modelo en los ejes X, Y o Z para un modelado rápido de objetos simétricos.

![Symmetry](symetry.gif)

---

### 📦 Gestión de Escena

#### Capas (Layers)
Organiza tu escena utilizando un sistema de capas robusto. Oculta, bloquea o visualiza partes específicas de tu modelo.

![Layers System](layers.gif)



## 📄 Licencia

Este proyecto está bajo la Licencia **MIT**.

```text
MIT License

Copyright (c) 2026 XocoStudio

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
