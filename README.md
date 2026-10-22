# co2rr-diffusion-model
Modelado numérico de la difusión de CO₂ hacia un electrodo en procesos de reducción 

## Preparar el cuaderno en VS Code

Desde la carpeta del proyecto, crea o activa el entorno virtual e instala las
dependencias:

```bash
python -m venv .venv
.venv/bin/python -m pip install -r requirements.txt
.venv/bin/python -m ipykernel install --user --name co2rr-diffusion \
  --display-name "Python (.venv) - CO2RR"
```

En Windows, usa `.venv\Scripts\python` en lugar de `.venv/bin/python`.

Después, abre `Etapa_1.ipynb` y selecciona el kernel **Python (.venv) - CO2RR**
en la esquina superior derecha. El kernel debe ser el mismo entorno donde se
instalaron `numpy`, `scipy` y `matplotlib`.
