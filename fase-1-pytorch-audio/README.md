# Fase 1 — PyTorch + audio (≈ Mes 1)

## Objetivo
Reorientar la base de ML a PyTorch y montar el pipeline "sonido → representación numérica".
No es otro curso entero: es situarse en el framework donde vive la investigación de audio.

## Recursos
- PyTorch — "Deep Learning with PyTorch: A 60 Minute Blitz" (tutorial oficial):
  https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html
- torchaudio (docs y tutoriales): https://pytorch.org/audio/stable/index.html
- librosa: https://librosa.org/doc/latest/index.html

## Qué hacer
- [ ] Blitz de PyTorch (tensores, autograd, un nn.Module mínimo).
- [ ] Reimplementar en PyTorch puro 1–2 cosas que ya hiciste en fastai/TF.
- [ ] Cargar un audio y generar: waveform, espectrograma, mel-espectrograma, MFCC.

## Entregable
Notebook en `notebooks/` que tome un audio propio y saque sus features (guardar como
`entregable/features.ipynb`). Con eso queda interiorizado el paso audio → tensores.

## Checklist de cierre
- [ ] Sé mover datos entre CPU/GPU y entiendo autograd.
- [ ] Sé pasar de un `.wav` a un mel-espectrograma y explicar cada eje.
