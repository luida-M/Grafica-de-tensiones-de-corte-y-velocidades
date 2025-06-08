# Distribución de Velocidades y Tensiones de Corte en un Flujo entre Cilindros Concéntricos

Este notebook resuelve y analiza el problema de flujo viscoso y estacionario de un fluido incompresible entre dos cilindros concéntricos, correspondiente a un ejercicio típico de la materia *Mecánica de Fluidos* en Ingeniería Industrial.

## ✅ Objetivos

- Determinar la **distribución de velocidades** ( Vz(r) en coordenadas cilíndricas aplicando la solución analítica de la ecuación de Navier-Stokes para flujo unidimensional.
- Calcular las **constantes de integración** ( C1) y ( C2) a partir de las condiciones de contorno (velocidades dadas en los cilindros).
- Obtener el perfil de la **tensión de corte** que actúa sobre el fluido, en función del gradiente radial de velocidad.
- Representar gráficamente la distribución de velocidad y la tensión de corte entre los cilindros.

## 📌 Contenido

1. **Formulación teórica**: se parte del modelo de flujo laminar entre cilindros en coordenadas cilíndricas.
2. **Desarrollo analítico**: se integra la ecuación de momento axial y se aplican condiciones de frontera.
3. **Cálculo de la tensión de corte** 
4. **Visualización**: se grafican tanto la distribución de velocidad como la tensión de corte usando Python y matplotlib.

## 🧮 Parámetros utilizados

- Radio interior: \( R_1 = 0.01 \, m \)
- Radio exterior: \( R_2 = 0.015 \, m \)
- Velocidad en el cilindro exterior: \( U = 0.02 \, m/s \)
- Viscosidad dinámica: \( \mu = 1 \times 10^{-3} \, Pa \cdot s \)

## 📈 Resultados esperados

- Perfil de velocidad con forma logarítmica decreciente hacia el cilindro interior.
- Tensión de corte máxima en el cilindro interior y mínima en el cilindro exterior.

