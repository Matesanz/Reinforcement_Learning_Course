# 👋 Curso sobre Reinforcement Learning

## 🙂 Descripción

En este curso se incluye **todo lo básico relacionado con el Aprendizaje por Refuerzo**. Desde los conceptos más básicos, como qué es una cadena de Markov, hasta conceptos más interesantes como la **inclusión de Redes Neuronales** en algoritmos de RL. Para ello, cada una de las clases cuenta con un Jupyter Notebook ejecutable con toda la teoría y con imágenes de esquemas que ayudan a una mejor comprensión. Esta pensado para que sea un **curso desde 0**, por ello, tanto si eres principiante, como si quieres refrescar conocimientos, este curso es para ti.

## 🔖 Tabla de Contenidos

- [👋 Curso sobre Reinforcement Learning](#-curso-sobre-reinforcement-learning)
  - [🙂 Descripción](#-descripción)
  - [🔖 Tabla de Contenidos](#-tabla-de-contenidos)
- [📜 Temas](#-temas)
  - [0️⃣ Introducción a Reinforcement Learning](#0️⃣-introducción-a-reinforcement-learning)
  - [1️⃣ Introducción a Reinforcement Learning 🏗️ (En construcción...)](#1️⃣-introducción-a-reinforcement-learning-️-en-construcción)
  - [2️⃣ Ecuación de Bellman y Q-Learning 🏗️ (En construcción...)](#2️⃣-ecuación-de-bellman-y-q-learning-️-en-construcción)
  - [3️⃣ Deep Reinforcement Learning 🏗️ (En construcción...)](#3️⃣-deep-reinforcement-learning-️-en-construcción)
- [⚡ Quick-Start: usando remote containers](#-quick-start-usando-remote-containers)

Este curso está dividido en varias partes:

# 📜 Temas

Para ejecutar los notebooks la mejor forma es [usar docker](#-quick-start-usando-remote-containers). En apenas **unos minutos y sin instalar nada** tendrás acceso a todos los notebooks. 🤯

## 0️⃣ Introducción a Reinforcement Learning
- Agente y Entorno
- Recompensas, Observaciones y Acciones
- Equilibrio Exploración Explotación
- Maximizar la Recompensa a largo plazo
- Descubriendo Gym: Creando mi primer entorno
- Descubriendo Gym: Creando mi primer agente
  
![Reinforcement Learning Intro](https://user-images.githubusercontent.com/44867923/139915800-8224bede-c52b-47d1-bb22-2e9624687831.jpg)

## 1️⃣ Introducción a Reinforcement Learning 🏗️ (En construcción...)
- Cadenas de Markov
- Procesos de Recompensa de Markov
- Procesos de Decision de Markov


![Markov Decision Process](https://user-images.githubusercontent.com/44867923/139942084-eaddeb99-2e9b-4f7b-9421-d6de4c83ff2f.jpg)

## 2️⃣ Ecuación de Bellman y Q-Learning 🏗️ (En construcción...)
- Las acciones en los Procesos de decisión de Markov
- Calculando el Valor de los Estados
- Q: El valor de las acciones
- Programación Dinámica: Iteración de Valores
- Diferencias Temporales: Q-learning

![Q-learning](https://user-images.githubusercontent.com/44867923/139942851-e38359ef-9fc4-4956-b591-57b4db658d77.jpg)

## 3️⃣ Deep Reinforcement Learning 🏗️ (En construcción...)
- Breve introducción al Deep Learning
- Redes neuronales y Reinforcement Learning
- Método Cross-Entropy
- Deep Q-learning

![Deep Learning en Reinforcement Learning](https://user-images.githubusercontent.com/44867923/139941983-7d8b1894-5dd9-4568-b04c-3a316af8ed85.jpg)


# ⚡ Quick-Start: usando remote containers

**1. Instala el Plugin de VSCode de [Remote Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)**

```
# Presiona Ctrl + shift + p
# Pega ext install ms-vscode-remote.remote-containers
# Presiona Enter
```

**2. Abre el entorno de desarrollo**

```
# Presiona Ctrl + shift + p
# Busca: Remote-Containers: Rebuild and Reopen in container
# Presiona Enter (y espera, la primera vez tarda unos minutos)
```

**3. Abre los Notebooks**

Abre el buscador y ve a [http://127.0.0.1:8888/](http://127.0.0.1:8888/)
