# PETDEX

PETDEX es una Pokédex de animales domésticos que representa servicios de AWS de forma visual y narrativa.

Cada animal encarna un servicio del ecosistema AWS, combinando:
- metáfora animal
- explicación técnica accesible (nivel Cloud Practitioner)
- una estética inspirada en una Pokédex clásica

El objetivo no es memorizar servicios, sino entenderlos.

---

## Qué es PETDEX

- Un sitio web estático (HTML + CSS)
- Pensado para aprendizaje, divulgación y portfolio
- Diseñado para desplegarse fácilmente en Amazon S3
- Sin frameworks ni dependencias externas

---

## Concepto

En PETDEX:
- Cada animal representa un servicio de AWS
- El comportamiento del animal refleja:
  - cómo funciona el servicio
  - cuándo brilla
  - cuándo puede dar problemas
- La interfaz imita una Pokédex:
  - vista general tipo catálogo
  - fichas individuales con navegación


---

## Cómo funciona la interfaz

### Vista general (Petdex)

Cada tarjeta muestra:
- nombre del animal
- tipo de servicio (Compute, Serverless, etc.)
- nombre del servicio AWS

### Vista ficha individual

Al hacer clic sobre una tarjeta:
- se abre una ficha ampliada
- aparece:
  - descripción larga
  - movimiento especial
- se puede navegar con:
  - botones visuales de navegación
  - teclas izquierda y derecha del teclado
  - tecla Escape para cerrar

---

## Detalles de diseño

- Estética inspirada en una Pokédex
- Animaciones suaves y no intrusivas
- Bordes de las tarjetas según el tipo de servicio
- Diseño responsive (desktop, tablet y móvil)
- Navegación accesible con teclado

---

## Despliegue

PETDEX puede desplegarse fácilmente en:

### GitHub Pages
- usando `index.html` o `index2.html` como página principal

### Amazon S3
- bucket público con hosting estático
- pensado expresamente para ese entorno

---

## Autoría

Proyecto creado por:
- Sara Gavilán
- Clara Bueno

---

## Notas finales

PETDEX no pretende ser documentación oficial de AWS.  
Es una herramienta creativa para aprender, explicar y recordar conceptos técnicos de forma más humana.
