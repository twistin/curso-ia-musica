# Fase 3 — ML dentro de SuperCollider con FluCoMa (≈ Meses 3–4)

## Objetivo
Aterrizar el ML en tu propio entorno y usarlo como material sonoro, no como abstracción.
Aquí empieza a rentar de verdad y es directamente demostrable en clase.

## Recursos
- FluCoMa (Fluid Corpus Manipulation): https://www.flucoma.org/
  - Learn / tutoriales: https://learn.flucoma.org/
- SCMIR (music information retrieval en SC, Nick Collins):
  https://composerprogrammer.com/code.html

## Qué hacer
- [ ] Instalar FluCoMa en SuperCollider.
- [ ] Tutoriales oficiales (descriptores, datasets, KDTree, escalado).
- [ ] Analizar un banco de sonidos propio, reducir con UMAP a 2D y recorrerlo en vivo.

## Entregable
Sistema de navegación por corpus o síntesis concatenativa con material propio.
Código SC en `sc/`; describir el patch/instrumento en `entregable/`.

## Nota docente
Esta fase es fácilmente convertible en una práctica de Nuevas Tecnologías: el alumnado
ve el ML como espacio sonoro navegable.

## Checklist de cierre
- [ ] Sé extraer descriptores y meterlos en un `FluidDataSet`.
- [ ] Entiendo reducción de dimensionalidad (UMAP/PCA) aplicada a timbre.
- [ ] Tengo un mapeo gesto → punto en el espacio latente que suena.
