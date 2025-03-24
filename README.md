# 💻 Quantum Systems Simulator — Capítulo 4

Este proyecto simula los sistemas cuánticos presentados en el **Capítulo 4** del libro *Quantum Computing for Computer Scientists* (Yanofsky y Mannucci), utilizando Python y Jupyter Notebooks.

---

## 📚 Descripción del sistema

El sistema principal modela una **partícula cuántica confinada a un conjunto discreto de posiciones** sobre una línea, como se describe en la **sección 4.1** del libro.

A partir de este modelo, se implementan funcionalidades para calcular:

1. **Probabilidad de encontrar la partícula** en una posición específica.
2. **Probabilidad de transición** de un estado ket a otro.
3. **Amplitud de transición entre vectores.**
4. **Media y varianza** de un observable dado un estado ket.
5. **Valores propios de un observable** y sus probabilidades de transición.
6. **Evolución dinámica** del sistema con matrices unitarias aplicadas en secuencia.

---

## Estructura del repositorio

```bash
.
├── README.md
└── taller.ipynb  
```

---

## Instalacion de dependencias  

Requiere Python 3.8+ y Jupyter. Puedes instalar las librerías necesarias con:

```bash
pip install numpy
pip install matplotlib
```

---
## Como ejecutar el repositorio

1. Clonar el repositorio.
```bash
git clone https://github.com/brayanvaldes/caputulo4

```

2. Abrir el entorno jupiter.


## Ejercicios implementados
| Ejercicio	| Descripción |  
|:-:|:-:|
|4.3.1	| Transición a autovectores de un observable |
| 4.3.2 |	Media, varianza y distribución de autovalores	|
| 4.4.1 |	Verificación de matrices unitarias	|
| 4.4.2	| Evolución cuántica de 3 pasos	|

---

## Discusiones teoricas
|Tema	| Archivo |
|:-:|:-:|
| Discusión del Ejercicio 4.5.2 | (Estado general de múltiples partículas)	| 
| Discusión del Ejercicio 4.5.3 |(Separabilidad vs Entrelazamiento)	|

---

## Autor
Desarrollado por Brayan Valdes como parte del estudio de simulaciones cuánticas para el curso de ciencias naturales y tecnologia.

---

# Referencias
Yanofsky, N. S., & Mannucci, M. A. (2008). Quantum Computing for Computer Scientists. Cambridge University Press.