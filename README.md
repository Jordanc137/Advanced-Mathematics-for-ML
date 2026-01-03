Math for ML: Fundamentos con Beamer
Este repositorio contiene las fuentes de mi presentación sobre la matemática "pesada" detrás del Machine Learning. La idea no es solo listar temas, sino dar definiciones formales (SVD, RKHS, KL Divergence) con un diseño limpio y profesional usando el tema Metropolis.

Decidí usar un esquema de color Verde Bosque (Forest Green) porque el azul por defecto de Beamer está muy visto y quería algo más sobrio y elegante para hablar de optimización y espacios de Hilbert.

Contenido técnico
La presentación cubre cuatro pilares que suelen ser "cajas negras" para muchos:

SVD (Singular Value Decomposition): Más allá de PCA, el rigor de la norma de Frobenius.

Matrices de segundo orden: Por qué la Hessiana determina el learning rate en optimizadores avanzados.

Teoría de la Información: Divergencia de KL explicada para VAEs.

RKHS: El Teorema de Representación para kernels.

Stack de diseño
Motor: LaTeX / Beamer.

Tema: Metropolis.

Fuentes: Fira Sans (incluida en Metropolis).

Iconos: FontAwesome 5.

Paleta: Custom #223329 (Forest Green).

Cómo compilar esto
Si usas Overleaf, solo tienes que subir el .tex y el .gitignore.

Si compilas en local (TeX Live / MikTeX):

Asegúrate de tener instalado el paquete metropolis (mtheme).

Usa pdflatex (necesitarás un par de pasadas para las referencias).

Asegúrate de que fontawesome5 esté actualizado en tu distribución.

Estructura del repo
main.tex: El código fuente principal.

img/: Gráficos vectoriales (PDF/EPS) para no perder resolución.

.gitignore: Configurado para ignorar la "basura" que genera LaTeX (.aux, .nav, .snm, etc.).
