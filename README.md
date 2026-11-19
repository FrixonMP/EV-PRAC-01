# EV-PRAC-01

Transcripción y evidencias de la evaluación práctica **EV-PRAC-01**.

## Estructura del repositorio

- `README.md`: Instrucciones de compilación y estructura del trabajo.
- `evidencias/`: Fotografías de las hojas originales escritas a mano (`hoja-01.jpg`, `hoja-02.jpg` y `hoja-03.jpg`).
- `main.tex`: Transcripción fiel de la prueba escrita a mano con el anexo de fotografías al final.
- `referencias.bib`: Base bibliográfica en formato BibTeX utilizada por `main.tex`.
- `main.pdf`: Documento PDF compilado a partir de `main.tex`.

## Instrucciones de compilación

- **Compilador:** `pdflatex` junto con `bibtex` (TeX Live / MiKTeX)
- **Archivo principal:** `main.tex`
- **Dependencias / paquetes:** `inputenc`, `fontenc`, `helvet`, `geometry`, `graphicx`, `array`, `tabularx`, `colortbl`, `xcolor`, `enumitem`, `fancyhdr`, `lastpage`, `tcolorbox` (con opción `most`), `amsmath`, `natbib` (con opciones `numbers,sort&compress`), `url`, `caption` y `hyperref`, además del estilo bibliográfico `plainnat`.

### Orden de comandos

Abre una terminal dentro de la carpeta donde se encuentra `main.tex` y `referencias.bib`, y ejecuta:

```bash
pdflatex -interaction=nonstopmode main.tex
bibtex main
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
