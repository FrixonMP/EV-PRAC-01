# EV-PRAC-01

Transcripción y evidencias de la evaluación práctica **EV-PRAC-01** (Caso **FRÍOVAC**), asignatura Ingeniería de Requerimientos (ISR-401), UTEQ.

## Estructura del repositorio

* `README.md`: Instrucciones de compilación y estructura del trabajo.
* `evidencias/`: Fotografías de las hojas originales escritas a mano (`hoja-01.jpg`, `hoja-02.jpg`, ...).
* `main.tex`: Transcripción fiel de la prueba escrita a mano con el anexo de fotografías al final.
* `main.pdf`: Documento PDF compilado a partir de `main.tex`.

## Instrucciones de compilación

* **Compilador:** `pdflatex` (TeX Live / MiKTeX)
* **Archivo principal:** `main.tex`
* **Dependencias / paquetes:** Paquetes estándar de $\LaTeX$ utilizados en el documento (por ejemplo: `inputenc` / `fontenc`, `babel` en español, `geometry`, `graphicx`, `booktabs`, `array`, `longtable`, `hyperref`). *Revisa el preámbulo de `main.tex` para confirmar los paquetes exactos usados.*

### Orden de comandos

Abre una terminal dentro de la carpeta donde se encuentra `main.tex` y ejecuta:

```bash
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
