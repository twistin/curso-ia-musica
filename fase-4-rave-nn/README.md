# Fase 4 — Síntesis neuronal: RAVE + nn.ar (≈ Meses 4–6)

## Objetivo
Integrar síntesis neuronal en tiempo real dentro de tu live coding, primero con modelos
pre-entrenados y luego con un modelo entrenado por ti sobre corpus propio.

## Recursos
- RAVE (ACIDS-IRCAM, Antoine Caillon): https://github.com/acids-ircam/RAVE
- nn.ar (extensión de SuperCollider, elgiano): https://github.com/elgiano/nn.ar
- Modelos pre-entrenados ACIDS-IRCAM: https://acids-ircam.github.io/rave_models_download
- Modelos CC (Intelligent Instruments Lab): https://huggingface.co/Intelligent-Instruments-Lab/rave-models
- Transfer learning para entrenar más rápido: https://github.com/victor-shepardson/RAVE

## Qué hacer
### 4a — Modelos pre-entrenados (CPU, empieza aquí)
- [ ] Instalar nn.ar en la carpeta de Extensions de SuperCollider.
- [ ] Cargar un modelo pre-entrenado y usar forward / encode / decode.
- [ ] Transferencia de timbre y exploración del espacio latente en tiempo real.
- [ ] Integrarlo en tu flujo de live coding.

### 4b — Entrenar tu propio modelo (necesita GPU)
- [ ] Preparar dataset (ver `entrenamiento/`).
- [ ] Entrenar RAVE (Colab o máquina con tarjeta).
- [ ] Exportar a torchscript y cargarlo en nn.ar.

## Entregable
Pieza o performance de live coding construida sobre un modelo entrenado por ti.

## Aviso
Este es el punto de fricción del curso: entrenar requiere GPU y tiempo. No lo abordes
hasta cerrar la Fase 2. Empieza siempre por 4a con modelos ajenos.
