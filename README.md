# Ingeniería de Requerimientos (ISR-401) — Portafolio

## EV-PRAC-01 · Evaluación de la Unidad I

Transcripción fiel en LaTeX de la prueba escrita a mano. Las fotografías de las hojas están en `EV-PRAC-01/evidencias/`.

| Elemento | Valor |
|---|---|
| Compilador | `pdflatex` (TeX Live 2023 o superior, o MiKTeX) |
| Archivo principal | `EV-PRAC-01/main.tex` |
| Salida | `EV-PRAC-01/main.pdf` |
| Dependencias (paquetes) | `inputenc`, `fontenc`, `babel` (spanish), `geometry`, `array`, `longtable`, `enumitem` |

### Orden de comandos

```bash
git clone https://github.com/jriveras4-cmyk/ISR-401-Ingenieria-Requerimientos.git
cd ISR-401-Ingenieria-Requerimientos/EV-PRAC-01
pdflatex main.tex
pdflatex main.tex   # segunda pasada para longtable
```

En Overleaf: subir la carpeta `EV-PRAC-01`, compilador **pdfLaTeX**, documento principal `main.tex`.
