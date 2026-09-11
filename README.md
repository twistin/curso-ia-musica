# Curso IA + Música

Repositorio personal para organizar mi formación en inteligencia artificial aplicada
a la música, partiendo de una base de ML generalista (fastai, TensorFlow) y orientándola
hacia el audio, SuperCollider, el live coding y la docencia.

Diseñado para acceder al curso desde cualquier máquina (clonar → trabajar → push) y para
funcionar también como vault de Obsidian: todas las notas son markdown enlazable.

## Cómo usar este repo

- Cada fase tiene su carpeta con un `README.md` que define **objetivo**, **recursos**,
  **entregable** y **checklist**.
- `notebooks/` para el código Python de esa fase.
- `sc/` para el código SuperCollider (`.scd`).
- `notas/` para apuntes concretos de la fase; `notas/diario.md` (raíz) para el diario de aprendizaje transversal.
- `entregable/` guarda el resultado que cierra la fase (o su descripción si es una performance/audio pesado).
- Archivos grandes (audio, modelos) están ignorados por git: ver `.gitignore`.

## El arco (≈6 meses, ritmo realista)

| Fase | Foco | Corre en | Entregable |
|------|------|----------|------------|
| 0 | Setup y entorno | cualquier máquina | entorno reproducible |
| 1 | PyTorch + audio (torchaudio, librosa) | CPU | notebook audio → features |
| 2 | Deep learning para audio (The Sound of AI) | CPU/GPU ligera | clasificador de timbres |
| 3 | ML dentro de SuperCollider (FluCoMa) | CPU | navegación por corpus / concatenativa |
| 4 | Síntesis neuronal (RAVE + nn.ar) | GPU para entrenar | pieza de live coding con modelo propio |

Transversal: DDSP como marco conceptual, ISMIR para el estado del campo, y documentar
cada fase como material docente.

## Punto de fricción conocido

El salto de Fase 2 a Fase 4 (entrenar RAVE) es donde más gente abandona: requiere GPU y
tiempos de entrenamiento largos. Plan: usar primero modelos pre-entrenados y dejar el
entrenamiento propio para el final, sobre Colab o máquina con tarjeta.

## Progreso

- [ ] Fase 0 — Setup
- [ ] Fase 1 — PyTorch + audio
- [ ] Fase 2 — Deep learning para audio
- [ ] Fase 3 — FluCoMa en SuperCollider
- [ ] Fase 4 — RAVE + nn.ar
