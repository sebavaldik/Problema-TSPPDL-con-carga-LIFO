# TSPPDL — Trabajo Final CINF105 Optimización

Revisión bibliográfica crítica del **Traveling Salesman Problem with Pickup 
and Delivery and LIFO Loading (TSPPDL)**, desarrollada como trabajo final 
del curso CINF105 – Optimización, Universidad Andrés Bello (2026-1).

## ¿De qué trata?

El TSPPDL es una variante NP-difícil del problema del vendedor viajero donde 
un vehículo debe recoger y entregar cargas respetando una política LIFO 
(Last-In, First-Out): solo puede descargarse el ítem ubicado en la cima de 
la pila. Esto modela situaciones reales como reparto urbano con camiones de 
carga trasera, robots AGV en fábricas y transporte de carga frágil o peligrosa.

## Contenido del repositorio

- `GrupoX_TSPPD_paper.pdf` — Paper breve en formato IEEE (4–6 páginas)  
- `GrupoX_TSPPD_poster.pdf` — Póster académico divulgativo  
- `GrupoX_TSPPD_paper.tex` — Fuente LaTeX del paper  
- `GrupoX_TSPPD_poster.tex` — Fuente LaTeX del póster  

## Temas cubiertos

- Definición formal y formulación MILP (TSPPDL3)
- Complejidad computacional (NP-difícil, reducción desde ATSP)
- Aplicaciones reales: logística urbana, AGV, carga especial
- Estado del arte: Branch-and-Cut, VNS sobre árboles, Deep RL
- Rol del solver heurístico LKH-3 de Helsgaun (2017)
- Brechas abiertas y tendencias post-2020

## Autores

Anakin Benavides · Sebastián Valdovinos  
Facultad de Ingeniería — Universidad Andrés Bello