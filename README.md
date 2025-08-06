# Learning

This repository gathers my learning projects as submodules and classifies them according to the primary technologies used.

---

## 1. Project Index

| #   | Project                | Path                      |
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

## 2. Technology Classification

| Technology                     | Projects (indices) |
| ------------------------------ | ------------------ |
| **React**                      | 6, 7, 12           |
| **Static Pages (HTML/CSS)**    | 2, 8, 9            |
| **JavaScript (Vanilla + DOM)** | 1, 3, 4, 5, 10, 11 |

---

## 3. How to Work with Submodules

1. Clone this repository with all submodules:
   ```bash
   git clone --recursive git@github.com:manulzvz/learning.git
   ```

````

2. If you already cloned it without `--recursive`, initialize and download:

   ```bash
   git submodule update --init --recursive
   ```

3. To add new projects:

   ```bash
   git submodule add <repo-URL> <destination-folder>
   git commit -m "Add <project-name> as submodule"
   git push
   ```


````
