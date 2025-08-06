# Learning

Este repositorio agrupa mis proyectos de aprendizaje como submódulos y los clasifica según las tecnologías principales utilizadas.

---

## 1. Índice de proyectos

| #   | Proyecto               | Ruta                      |
| --- | ---------------------- | ------------------------- |
| 1   | etch-a-sketch          | `etch-a-sketch/`          |
| 2   | homepage               | `homepage/`               |
| 3   | js-battleship          | `js-battleship/`          |
| 4   | library                | `library/`                |
| 5   | memory-card            | `memory-card/`            |
| 6   | cv-application         | `cv-application/`         |
| 7   | react-lifecycle-logger | `react-lifecycle-logger/` |
| 8   | restaurant-page        | `restaurant-page/`        |
| 9   | signup-form            | `signup-form/`            |
| 10  | tic-tac-toe            | `tic-tac-toe/`            |
| 11  | to-do-list             | `to-do-list/`             |
| 12  | weather-app            | `weather-app/`            |

---

## 2. Clasificación por tecnología

| Tecnología                       | Proyectos (índices) |
| -------------------------------- | ------------------- |
| **React**                        | 6, 7, 12            |
| **Páginas estáticas (HTML/CSS)** | 2, 8, 9             |
| **JavaScript (Vanilla + DOM)**   | 1, 3, 4, 5, 10, 11  |

---

## 3. Cómo trabajar con submódulos

1. Clona este repositorio con todos los submódulos:

   ```bash
   git clone --recursive git@github.com:manulzvz/learning.git
   ```

2. Si ya lo clonaste sin `--recursive`, inicializa y descarga:

   ```bash
   git submodule update --init --recursive
   ```

3. Para agregar nuevos proyectos:

   ```bash
   git submodule add <URL-del-repo> <carpeta-destino>
   git commit -m "Agrega <nombre-proyecto> como submódulo"
   git push
   ```
