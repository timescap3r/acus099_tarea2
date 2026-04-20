# ACUS099 — Tarea 2: Respuesta al impulso en salas

## Objetivo

Elaborar y publicar una página web por grupo de trabajo en GitHub, mostrando mediante recursos audiovisuales el trabajo realizado en la captura y procesamiento de registros de audio de respuesta al impulso en tres recintos de la UACh o ciudad de Valdivia.

---

## Organización

- Grupos de 2 ó 3 estudiantes
- Se deben mantener los grupos ya formados en el curso

---

## Actividades

1. Seleccionar 2 recintos adicionales a la cámara reverberante de AcústicaUACh.
2. Realizar mediciones de respuesta al impulso según ISO 3382.
3. Registrar:
   - Respuesta al impulso en cada recinto
   - Voz en cámara anecoica
   - Instrumento musical en cámara anecoica
4. Registrar imágenes del proceso (in-situ).
5. Realizar convoluciones entre:
   - Voz anecoica + respuesta al impulso
   - Instrumento + respuesta al impulso
6. Generar una página web con todos los resultados.

---

## Ejemplo de procesamiento

- Voz anecoica * impulso recinto → Convolución  
- Instrumento * impulso recinto → Convolución  

---

## Entrega

Cada grupo debe generar una página web dentro del repositorio (`docs/`) que incluya:

### Contenido obligatorio:

- Nombre del grupo  
- Integrantes  
- Equipamiento utilizado  
- Procedimiento de medición  
- Fotografías in-situ  
- Audios en cada etapa  
- Formas de onda de cada audio  
- Resultados de convolución  

---

## Estructura del repositorio

```text
assets/
  ├── audio/
  ├── images/
  └── plots/

docs/
  └── index.md   ← página web

notebooks/
  └── 01_convolucion.ipynb

scripts/
data/
results/
```

## Criterios de evaluación

Se evaluará:

- Claridad de los datos mostrados  
- Calidad de los registros audiovisuales  
- Calidad de gráficos (formas de onda, etc.)  
- Organización del repositorio  
- Orden y presentación de la página web  

---

## Requisitos importantes

- Todos los audios deben estar correctamente etiquetados  
- Las figuras deben ser claras y legibles  
- La página web debe ser ordenada y comprensible  

---

## Recomendación

Se recomienda utilizar el notebook proporcionado para generar las figuras y realizar las convoluciones, asegurando consistencia en los resultados entre grupos.
