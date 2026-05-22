# Curso Abierto SIC 2026

![Samsung Innovation Campus](https://img.shields.io/badge/Samsung-Innovation%20Campus-blue?style=flat-square)
![ONG Innovacien](https://img.shields.io/badge/ONG-Innovacien-orange?style=flat-square)
![Python](https://img.shields.io/badge/Python-3.10%2B-green?style=flat-square)
![Licencia](https://img.shields.io/badge/Licencia-MIT-lightgrey?style=flat-square)

Repositorio oficial del **Curso Abierto de nivelación** del programa Samsung Innovation Campus (SIC) Chile 2026, ejecutado por [ONG Innovacien](https://innovacien.org).

La iniciativa busca democratizar el acceso al código a través de un curso intensivo de 50 horas, modalidad 100% flexible y sin requisitos previos de ingreso.

---

## 🚀 ¿Cómo usar este repositorio?

Cada notebook puede abrirse directamente en Google Colab haciendo clic en el botón **"Open in Colab"** que aparece al inicio de cada archivo, o clonando el repositorio:

```bash
git clone https://github.com/davidlealo/curso_abierto_sic_2026.git
```

No se requiere instalación previa. Todo el código está pensado para ejecutarse en la nube (Google Colab) sin configuración adicional.

---

## 📚 Contenido del Curso

### Clase 1 — Fundamentos de Python
**`001_clase_abierta.ipynb`**

Clase introductoria que cubre los bloques fundamentales del lenguaje. Se exploran los tipos de datos numéricos (`int`, `float`, `complex`), booleanos, cadenas de texto con operaciones y f-strings, y las principales estructuras de datos (`list`, `tuple`, `range`, `dict`, `set`, `frozenset`, `NoneType`). Se aborda la conversión entre tipos (casting) y verificación con `type()` e `isinstance()`. La segunda mitad profundiza en las 35 palabras reservadas de Python 3.12+ organizadas por categoría. Cierra con un ejercicio práctico de lectura de datos CSV — primero con Python puro, luego con `pandas` — usando el dataset `auto-mpg`.

**Temas:** tipos de datos · keywords · estructuras de datos · casting · pandas · lectura de CSV

---

### Clase 2 — Funciones Built-in y Estructuras de Control
**`002_clase_abierta.ipynb`**

Recorre sistemáticamente las funciones integradas de Python en 9 categorías: conversión de tipos, funciones matemáticas, iteración y secuencias, entrada/salida, objetos y atributos, clases y herencia, alcance de variables, evaluación/ejecución, y otras utilidades. La segunda mitad cubre las estructuras de control: condicionales (`if/elif/else`, operador ternario, `match/case`), bucles (`for` y `while`), control de flujo (`break`, `continue`, `pass`), manejo de excepciones (`try/except/finally`, `raise`, excepciones personalizadas), gestión de contexto con `with`, comprensiones de lista/diccionario/conjunto, expresiones generadoras y patrones de uso común.

**Temas:** built-ins · condicionales · bucles · excepciones · comprensiones · match/case

---

### Clase 3 — Práctica de Bucles `for` y `while`
**`003_clase_abierta.ipynb`**

Sesión enteramente práctica orientada a consolidar el uso de bucles mediante ejercicios resueltos en vivo. Con `for`: iterar sobre listas, rangos y cadenas; acumular sumas; imprimir múltiplos; aplicar descuentos; contar caracteres; construir listas de cuadrados; filtrar por condición. Con `while`: contador básico, centinela con palabra clave, validación de PIN con reintentos, vaciado de lista con `.pop()`, y calculadora acumuladora con `input()`.

**Temas:** for · while · ejercicios prácticos · input · lógica de negocio

---

### Clase 4 — Variables, Nomenclatura y Operadores
**`004_clase_abierta.ipynb`**

Explora el concepto de variable a nivel de memoria usando `id()`, mostrando en vivo cómo Python asigna y reasigna direcciones. Cubre las convenciones de nomenclatura (`camelCase`, `snake_case`, `PascalCase`, `kebab-case`, `SCREAMING_SNAKE_CASE`) y las reglas formales de Python para nombres de variables (PEP 8). La segunda mitad trabaja el cuadro de precedencia de operadores completo, el operador de módulo `%` con casos prácticos (paridad, ciclos, conversión de unidades), y los operadores de comparación (`==`, `!=`, `>`, `<`, `>=`, `<=`) con ejemplos de contexto real.

**Temas:** variables · memoria · nomenclatura · PEP 8 · precedencia · módulo · comparación

---

### Clase 5 — Emprender en Tecnología: Startup Chile y casos reales
**`005_clase_abierta.ipynb`**

Sesión especial en formato webinar con Patricia Ibáñez de **Startup Chile** y **Sebastián Doménech**, fundador de [Agrolytics](https://agrolyticsapp.com/). La conversación conecta las habilidades técnicas del curso con el mundo real del emprendimiento tecnológico en Chile: cómo Python, datos e IA pueden ser la base para construir un producto, qué apoyos existen desde CORFO, y cómo funciona el programa BIG de Startup Chile.

🎥 **Video:** [youtu.be/Rctcf4k1xjQ](https://youtu.be/Rctcf4k1xjQ)

**Recursos:**
- 🌱 [Agrolytics](https://agrolyticsapp.com/) — empresa de Sebastián Doménech
- 💼 [LinkedIn Sebastián](https://www.linkedin.com/in/sebastian-domenech/)
- 🚀 [Startup Chile](https://startupchile.org/)
- 📄 [Bases BIG 11](https://startupchile.org/content/uploads/resolucioxxn-electroxxnica-exenta-nxx1457-de-2025-de-corfo-modifica-bases-start-up-chile-big-11.pdf)
- 📘 [Brochure BIG 12](https://startupchile.org/content/uploads/brochure-big-12-esp-1.pdf)

---

## 🗂️ Estructura del repositorio

```
curso_abierto_sic_2026/
├── 001_clase_abierta.ipynb     # Fundamentos de Python
├── 002_clase_abierta.ipynb     # Built-ins y estructuras de control
├── 003_clase_abierta.ipynb     # Práctica de bucles
├── 004_clase_abierta.ipynb     # Variables, nomenclatura y operadores
├── 005_clase_abierta.ipynb     # Webinar: emprender en tecnología
├── AportesEstudiantes/         # Ejercicios y proyectos de estudiantes
└── README.md
```

---

## 🛠️ Requisitos

- Cuenta de Google (para usar Google Colab, sin instalación)
- O Python 3.10+ instalado localmente con Jupyter Notebook

```bash
pip install jupyter pandas
jupyter notebook
```

---

## 🤝 Contribuciones

¿Eres estudiante del curso? Puedes subir tus ejercicios y proyectos en la carpeta `AportesEstudiantes/`. Haz un fork del repositorio, agrega tu archivo y abre un Pull Request.

---

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

---

*Samsung Innovation Campus 2026 · ONG Innovacien · [innovacien.org](https://innovacien.org)*
