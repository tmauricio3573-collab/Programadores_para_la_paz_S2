# Programadores para la Paz – Semana 2 Día 5

## Project Overview
A static HTML community participation form ("Formulario Participa") for the "Programadores para la Paz" educational program.

## Structure
- `semana2/index.html` — Main HTML form page
- `semana2/styles.css` — Stylesheet
- `semana2/checklist-accesibilidad.txt` — Accessibility checklist
- `semana2/reflexion-verificacion.txt` — Reflection on responsible verification
- `instrucciones/guia-practica-semana2-dia5.txt` — Activity guide

## Running the App
The app is served as a static site using Python's built-in HTTP server:
```
python3 -m http.server 5000 --directory semana2
```
Runs on port 5000 via the "Start application" workflow.

## Deployment
Configured as a **static** deployment with `publicDir: semana2`.
