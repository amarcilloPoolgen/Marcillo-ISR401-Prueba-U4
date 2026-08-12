# Prueba Práctica — Unidad IV — Ingeniería de Requisitos (ISR-401)

**Caso:** Sistema de Gestión de Pedidos
**Estudiante:** Alberto Jeanpool Marcillo Ponce
**Docente:** Ing. Gleiston Guerrero Ulloa, PhD.

## Contenido del repositorio

```
├── main.tex                  # Archivo principal LaTeX (respuestas P1–P10)
├── main.pdf                  # PDF compilado
├── p1_diagrama_de_clases.png           # P1 — Diagrama de clases UML
├── p2_diagrama_de_actividades.png           # P2 — Diagrama de actividades UML
├── p3_maquina_de_estados.png           # P3 — Máquina de estados
├── captura_evaluacion.png    # Captura: resumen del cuestionario (SGA)
├── captura_resumen.png       # Captura: revisión del intento (SGA)
└── README.md                 # Este archivo
```

## Requisitos previos

- Distribución LaTeX con `pdflatex` (por ejemplo, TeX Live 2023 o superior, o MiKTeX).
- Paquetes utilizados (incluidos en cualquier instalación completa de TeX Live/MiKTeX):
  `inputenc`, `babel` (spanish), `geometry`, `graphicx`, `longtable`, `booktabs`,
  `array`, `hyperref`, `enumitem`, `titlesec`, `xcolor`.

## Instrucciones de compilación

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/TU-USUARIO/TU-REPOSITORIO.git](https://github.com/amarcilloPoolgen/Marcillo-ISR401-Prueba-U4/edit/main/README.md
   cd TU-REPOSITORIO
   ```

2. Compilar el archivo principal con `pdflatex` (se ejecuta dos veces para
   resolver referencias e hipervínculos correctamente):
   ```bash
   pdflatex -interaction=nonstopmode main.tex
   pdflatex -interaction=nonstopmode main.tex
   ```

3. El PDF resultante se genera como `main.pdf` en la misma carpeta.

> **Archivo principal:** `main.tex`
> **Compilador:** `pdflatex`
> **Dependencias:** las 5 imágenes PNG listadas arriba deben estar en la misma
> carpeta que `main.tex` (rutas relativas, sin subcarpetas).

## Notas

- No se usa `referencias.bib`; el documento no incluye bibliografía citada con BibTeX.
- Los diagramas (P1, P2, P3) se adjuntan como imagen (PNG), elaborados a partir
  de un boceto manual y digitalizados con herramientas de diagramación.
- Las capturas del cuestionario (resumen y revisión del intento) están
  incrustadas en la carátula del PDF, según lo exigido en la Sección 1 de la guía.
