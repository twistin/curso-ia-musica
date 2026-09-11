# Entorno reproducible

## Opción A — conda (recomendada)

```bash
conda create -n ia-musica python=3.11 -y
conda activate ia-musica
pip install -r requirements.txt
```

## Opción B — venv

```bash
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Comprobación rápida

```python
import torch, torchaudio, librosa
print("torch", torch.__version__)
print("cuda disponible:", torch.cuda.is_available())
```

Si `cuda disponible` es False no pasa nada para las fases 1–3: van en CPU.
La GPU solo es imprescindible para entrenar RAVE en la fase 4 (ahí, Colab o máquina con tarjeta).
