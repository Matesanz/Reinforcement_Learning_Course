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

## 1️⃣ Ecuación de Bellman: El valor de los estados
- V-table: asignando un valor a cada estado
- Ecuación de Bellman: calculando V para cada estado
- Cálculo de la Política usando la V-table


![Bellman_equation State_Value](https://user-images.githubusercontent.com/44867923/140994794-51d739af-eb70-4e6a-9036-b925f23ab7fd.jpg)

## 2️⃣ Ecuación de Bellman: El valor de las acciones
- Las acciones en los Procesos de decisión de Markov
- Q: El valor de las acciones
- Programación Dinámica: Iteración de Valores

![Q-value](https://user-images.githubusercontent.com/44867923/141012134-09ff0d88-4ce9-43af-8b04-d535cf24d897.jpg)

## 3️⃣ Q Learning
- Diferencias Temporales: Q-learning
- Alpha: aprender más de lo nuevo o de lo viejo
- Gamma: cuanto más lejos en el futuro menos confianza
- La política Óptima

![Q-learning](https://user-images.githubusercontent.com/44867923/141012234-257d26af-bf05-4dad-b402-96b54c735f41.jpg)


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
