---
title: '📅 Plan de Estudio: Mecánica de Osciladores y Sistemas Variacionales'
drive_id: 18emAq3jpkR10PiyJAjJHaKJwQi0Taxiby9mN3LpupGA
drive_url: https://docs.google.com/document/d/18emAq3jpkR10PiyJAjJHaKJwQi0Taxiby9mN3LpupGA
modified_time: '2026-05-07T17:46:56.206Z'
source: google-drive
---

# **📅 Plan de Estudio: Mecánica de Osciladores y Sistemas Variacionales**

Este plan está estructurado para ejecutarse en **4 sesiones**, enfocándose en los puntos donde hubo errores en el quiz y conectándolos con el **Problem Set 1 (Hand & Finch)**.

## **🕒 Sesión 1: Cinemática y Energía (El "Core" del MAS)**

*Objetivo: No volver a confundir dónde la velocidad es máxima o mínima.*

- **Concepto Clave:** En los extremos (\$x = \pm A\$), la energía es 100% potencial (\$v=0\$). En el equilibrio (\$x = 0\$), la energía es 100% cinética (\$v\_{max}\$).

- **Actividades:**

  1.  Graficar \$x(t)\$, \$v(t)\$ y \$a(t)\$ una debajo de la otra. Identificar los desfases de \$\pi/2\$.

  2.  Deducción de la velocidad usando conservación de la energía: \$\frac{1}{2}kA^2 = \frac{1}{2}mv^2 + \frac{1}{2}kx^2\$.

- **Reto TutorIA:** Pídeme que te explique la relación entre el círculo de referencia y las proyecciones del MAS.

## **🕒 Sesión 2: Dependencia de Parámetros (\$g, L, m, k\$)**

*Objetivo: Dominar cómo cambia el sistema cuando cambian las condiciones externas.*

- **Concepto Clave:** El péndulo "siente" la gravedad, el resorte "siente" la masa.

  1.  Péndulo: \$T = 2\pi \sqrt{L/g}\$ (Si \$g \downarrow\$, \$T \uparrow\$).

  2.  Resorte: \$T = 2\pi \sqrt{m/k}\$.

- **Actividades:**

  1.  Análisis dimensional de ambas fórmulas para memorizarlas sin esfuerzo.

  2.  Resolver problemas de "relojes que se atrasan": ¿Qué pasa si llevas un reloj de péndulo a la cima del Everest o a la Luna?

- **Conexión Uniandes:** Revisa por qué en el problema de la esfera, cuando el ángulo es pequeño, el movimiento radial se comporta de forma logarítmica y no puramente oscilatoria.

## **🕒 Sesión 3: El Formalismo Lagrangiano (Preparación Problem Set)**

*Objetivo: Aplicar el principio de Hamilton al problema de la esfera.*

- **Concepto Clave:** Multiplicadores de Lagrange (\$\lambda\$) y restricciones unilaterales.

- **Actividades:**

  1.  Escribir el Lagrangiano en coordenadas polares: \$L = T - V = \frac{1}{2}m(\dot{r}^2 + r^2\dot{\theta}^2) - mgr \cos\theta\$.

  2.  Entender la condición de desprendimiento: El contacto se pierde cuando la fuerza de restricción \$\lambda\$ (fuerza normal) se hace cero.

  3.  **Lectura:** Hand & Finch, Capítulo 1 (Problemas 14 y 17 son clave para este nivel).

## **🕒 Sesión 4: Oscilaciones Avanzadas y Aproximaciones**

*Objetivo: Dominar el amortiguamiento y la expansión en serie de Taylor.*

- **Concepto Clave:** Casi cualquier potencial cerca de un mínimo estable se comporta como un oscilador armónico si el ángulo es suficientemente pequeño (\$\sin\theta \approx \theta\$).

- **Actividades:**

  1.  Derivar la ecuación del péndulo físico (Hand & Finch 7.7.2).

  2.  Practicar la expansión de Taylor para el término de energía potencial en el problema de la esfera cerca de \$\theta_0\$.

- **Simulación:** Si tienes Python o Mathematica, grafica la trayectoria del proyectil justo después del desprendimiento (\$t \> t^\*\$).

## **💡 Tips de Oro para el Quiz/Parcial**

1.  **Cuidado con las unidades:** Siempre verifica que dentro de la raíz de \$T\$ quede una unidad de tiempo.

2.  **La Normal no es siempre** \$mg \cos\theta\$**:** En dinámica, hay que sumarle el término centrípeto \$mR\dot{\theta}^2\$. El error en tu quiz sobre la gravedad te indica que debes analizar las fuerzas con más calma.

3.  **Visualiza:** Si el periodo aumenta, el sistema es más "lento". Una gravedad baja (Luna) hace que el péndulo caiga más lento, por lo tanto, el periodo es mayor.
