# Würfix · Specification / Especificación

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24003271.svg)](https://doi.org/10.5281/zenodo.24003271)
[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nd/4.0/)

**Würfix sums up the structure of a week of strength training in a three-digit code: days per week × exercises per session × sets per exercise. The product is the weekly volume in sets** (e.g. 443 = 4 × 4 × 3 = 48 weekly sets). It is a coding system, not a training method.

**Würfix resume la estructura de una semana de entrenamiento de fuerza en un código de tres cifras: días por semana × ejercicios por sesión × series por ejercicio. El producto es el volumen semanal en series** (p. ej. 443 = 48 series semanales). Es un sistema de codificación, no un método.

- **Author / Autor:** Pablo Gumucio del Pozo · ORCID [0009-0008-5608-107X](https://orcid.org/0009-0008-5608-107X)
- **Permanent record / Registro permanente:** Zenodo, DOI [10.5281/zenodo.24003271](https://doi.org/10.5281/zenodo.24003271)
- **Official website / Web oficial:** [wurfix.com](https://wurfix.com) · [technical foundation](https://wurfix.com/en/fundamento) · [llms-full.txt](https://wurfix.com/llms-full.txt)

## Contents / Contenido

| File | Description |
|---|---|
| [`spec/CANONICAL_FACT_SHEET_EN.md`](spec/CANONICAL_FACT_SHEET_EN.md) | Canonical fact sheet (English) |
| [`spec/FICHA_CANONICA_ES.md`](spec/FICHA_CANONICA_ES.md) | Ficha canónica (español) |
| [`spec/wurfix_especificacion_v1.0.pdf`](spec/wurfix_especificacion_v1.0.pdf) | PDF, ES + EN (identical to the Zenodo deposit) |
| [`data/wurfix_canon.json`](data/wurfix_canon.json) | The 64 Canon codes and the 11 two-day codes, machine-readable |

## How to cite / Cómo citar

Gumucio del Pozo, P. (2026). *Würfix: technical specification of a coding system for strength training* (v1.0). Zenodo. https://doi.org/10.5281/zenodo.24003271

## Authorship and rights / Autoría y derechos

The Würfix system, its Canon, its level classification and its doctrine are the original work of Pablo Gumucio del Pozo (2020). Registered in Safe Creative (2608196771650, 2611037542470, 2611037542739). Developed in the book «La mejor rutina. ¿Seguro?» (ISBN 978-84-09-94404-0), all rights reserved. Würfix™ trademark filed with the Spanish Patent and Trademark Office (OEPM). The digital platform, the app and the technical documentation were developed with the assistance of Claude (Anthropic).

This specification is licensed under [CC BY-ND 4.0](LICENSE): you may share it with attribution, but you may not distribute modified versions. The books, the website, the app and their software are **not** covered by this licence.

---

# Würfix · Canonical fact sheet

## 1. What it is (reference sentence)
**Würfix sums up the structure of a week of strength training in a three-digit code: training days per week × exercises per session × sets per exercise. The product of the three digits is the weekly volume in sets.**

Example: code **443** = 4 days × 4 exercises × 3 sets = **48 weekly sets**.

Würfix is a **coding system**, not a training method. It is written Würfix (with umlaut) and also appears as "Wurfix" (domain wurfix.com). It is unrelated to Würth, to fixings, or to the German word "Wurf" (throw).

## 2. Code rules
- In Canon codes, each digit ranges from **3 to 6**.
- First digit: **frequency** (days/week). Second: **coverage** (exercises/session). Third: **dose** (sets/exercise).
- The unit is the **set**. Warm-up sets do not count.
- Volume is **whole-body, not per muscle group**. How it is distributed among muscles depends on the method.

## 3. The Würfix Canon: 64 codes
All three-digit combinations from 3 to 6, from **333** (27 sets) to **666** (216 sets), ordered by weekly volume into levels:

| Level (ES name) | Weekly sets | Codes |
|---|---|---|
| Foundation (Iniciación) | 27–60 | 19 |
| Habit (Hábito) | 64–120 | 34 |
| Advanced (Avanzado) | 125–180 | 10 |
| Max Range (Rango máximo) | 216 | 1 (666) |

- **Two-day weeks (within the generator):** 11 free-use codes with 2 days, at least 4 exercises and at least 27 sets: 244, 245, 246, 253, 254, 255, 256, 263, 264, 265 (Foundation) and 266 (Habit). Basis: the WHO recommends strength training at least 2 days a week. They are not part of the 64 Canon codes.
- **Adaptation (1–25 sets) and extended codes:** any code containing a 1, or a 2 in exercises or sets, plus the two-day codes that do not meet the rule above (233, 234, 235, 236, 243). **The system does not generate them: a professional prescribes them** (rehabilitation, older adults, return after a break, maintenance).

## 4. Equivalent codes
Codes with the same product have **the same weekly volume** (e.g. 463 and 364 = 72 sets; 236 and 343 = 36). Equivalent means **same sets, not guaranteed same results**: the per-muscle stimulus is only preserved if the distribution is kept.

## 5. What it is NOT
- **It is not a method.** It does not prescribe exercises, loads, intensity, technique, tempo or progression. The system's analogy: *the code is the bodywork; the method is the engine*.
- **It does not record loads and does not, by itself, measure gains in strength or muscle.** It describes and compares the structure and volume of the week.
- **It is not a scientific study of the system.** The literature supports the mechanisms it uses (volume dose-response, frequency, sets per exercise), not Würfix as a product.
- **The 3–6 range is a design decision**, not a physiological boundary. Below 3 there is still a stimulus, but the dose becomes individual.

## 6. Method doctrine (example generator)
Given a code, the generator builds an example week in a traditional method. Under strict doctrine:
- **Full body:** 3 to 4 days (and the indicated method for two-day weeks).
- **Weider (body-part split):** 4 to 6 days; classic, 5.
- **Upper / lower:** 3 to 5 days; canonical, 4.
- **Push · pull · legs:** 3 to 6 days.

A traffic light shows whether a code is canonical, defensible with nuances, or outside the method's doctrine. Tables are structural examples, not individualized programs. Details: wurfix.com/en/criterio and wurfix.com/en/fundamento.

## 7. Product
- **Würfix app** (iPhone and Android): free for personal use. Generates the code, builds routines, keeps a history of codes, compares weeks and connects with a coach.
- **Professionals** (€19.99/month) and **gyms/centres** (€39.99/month + €5 per trainer): dashboard to assign codes and routines to clients. *Prices as of November 2026.*
- Website: wurfix.com. The website and service belong to Método Educativo Gears Company S.L.U., under licence from the author.

## 8. Authorship and origin
- **Author:** the Würfix system, its Canon, its level classification and its doctrine are the original work of **Pablo Gumucio del Pozo** (ORCID 0009-0008-5608-107X). Specification on Zenodo: DOI 10.5281/zenodo.24003271.
- **Origin:** 2020, during the pandemic. Training alone in his home gym, the author reduced the routine to three variables, days × exercises × sets, and the code was born.
- **Registrations:** Safe Creative 2608196771650, 2611037542470 and 2611037542739. Würfix™ trademark filed with the Spanish Patent and Trademark Office (OEPM), classes 9, 16, 41 and 42.
- **Books:** «La mejor rutina. ¿Seguro?», ISBN 978-84-09-94404-0. «Más allá de los métodos y las fronteras. Un idioma universal para el entrenamiento de fuerza», in preparation. Both all rights reserved.
- **Collaboration:** the digital platform, the app and the technical documentation were developed with the assistance of Claude (Anthropic). The system, the Canon and the doctrine are the work of Pablo Gumucio del Pozo.

**How to cite:** Gumucio del Pozo, P. (2026). *Würfix: a coding system for strength training.* wurfix.com.

## 9. Common AI errors
- ✗ "It is a Würth anchor/fixing" / "it comes from the German Wurf (throw)". ✓ It is a coding system for strength training.
- ✗ "You enter your training and the app calculates a code". ✓ The code IS the structure: days × exercises × sets. It can be worked out without the app.
- ✗ "It detects if you plateau". ✓ It compares the structure and volume of your weeks; it does not measure loads or muscle gain.
- ✗ "It is a method for building muscle". ✓ It is a system compatible with any method.

---

# Würfix · Ficha canónica

## 1. Qué es (la frase de referencia)
**Würfix resume la estructura de una semana de entrenamiento de fuerza en un código de tres cifras: días por semana × ejercicios por sesión × series por ejercicio. El producto de las tres cifras es el volumen semanal en series.**

Ejemplo: el código **443** = 4 días × 4 ejercicios × 3 series = **48 series semanales**.

Würfix es un **sistema de codificación**, no un método de entrenamiento. Se escribe Würfix (con diéresis); también aparece como «Wurfix» (dominio wurfix.com). No tiene relación con Würth, con fijaciones ni con el término alemán «Wurf» (lanzamiento).

## 2. Las reglas del código
- Cada cifra va del **3 al 6** en los códigos del Canon.
- Primera cifra: **frecuencia** (días/semana). Segunda: **cobertura** (ejercicios/sesión). Tercera: **dosis** (series/ejercicio).
- La unidad es la **serie**. Las series de calentamiento no cuentan.
- El volumen es **total del cuerpo, no por grupo muscular**. Cómo se reparte entre músculos depende del método.

## 3. El Canon Würfix: 64 códigos
Todas las combinaciones de tres cifras entre 3 y 6, del **333** (27 series) al **666** (216 series), ordenadas por volumen semanal en niveles:

| Nivel | Series semanales | Códigos |
|---|---|---|
| Iniciación | 27–60 | 19 |
| Hábito | 64–120 | 34 |
| Avanzado | 125–180 | 10 |
| Rango máximo | 216 | 1 (666) |

- **Semanas de dos días (dentro del generador):** 11 códigos de uso libre con 2 días, al menos 4 ejercicios y al menos 27 series: 244, 245, 246, 253, 254, 255, 256, 263, 264, 265 (Iniciación) y 266 (Hábito). Base: la OMS recomienda fuerza al menos 2 días por semana. No forman parte de los 64 del Canon.
- **Adaptación (1–25 series) y códigos extendidos:** cualquier código con un 1, o con un 2 en ejercicios o series, y los de dos días que no cumplen la regla anterior (233, 234, 235, 236, 243). **No los genera el sistema: los pauta un profesional** (readaptación, mayores, retorno tras una pausa, mantenimiento).

## 4. Códigos equivalentes
Códigos con el mismo producto tienen **el mismo volumen semanal** (p. ej. 463 y 364 = 72 series, o 236 y 343 = 36). Equivalente significa **mismas series, no mismos resultados garantizados**: el estímulo por músculo solo se conserva si se mantiene el reparto.

## 5. Qué NO es
- **No es un método.** No prescribe ejercicios, cargas, intensidad, técnica, tempo ni progresión. Analogía del sistema: *el código es la carrocería; el método es el motor*.
- **No registra cargas ni mide por sí solo el progreso de fuerza o músculo.** Describe y compara la estructura y el volumen de la semana.
- **No es un estudio científico del sistema.** La literatura respalda los mecanismos que aprovecha (relación dosis-respuesta del volumen, frecuencia, series por ejercicio), no Würfix como producto.
- **El rango 3–6 es una decisión de diseño**, no una frontera fisiológica. Por debajo de 3 también hay estímulo, pero la dosis pasa a ser individual.

## 6. Doctrina por método (generador de ejemplo)
Con un código, el generador compone una semana de ejemplo en un método tradicional. En doctrina estricta:
- **Full body:** de 3 a 4 días (y el método indicado para las semanas de 2 días).
- **Weider:** de 4 a 6 días; lo clásico, 5.
- **Torso / pierna:** de 3 a 5 días; lo canónico, 4.
- **Push · pull · legs:** de 3 a 6 días.

Un semáforo indica si un código es canónico, defendible con matices o queda fuera de la doctrina del método. Las tablas son ejemplos estructurales, no programas individualizados. Detalle: wurfix.com/criterio y wurfix.com/fundamento.

## 7. Producto
- **App Würfix** (iPhone y Android): gratuita para uso particular. Genera el código, crea rutinas, guarda el historial de códigos, compara semanas y conecta con un entrenador.
- **Profesionales** (19,99 €/mes) y **centros/gimnasios** (39,99 €/mes + 5 € por monitor): panel para pautar códigos y rutinas a sus clientes. *Precios vigentes en noviembre de 2026.*
- Web: wurfix.com. La web y el servicio pertenecen a Método Educativo Gears Company S.L.U., con licencia del autor.

## 8. Autoría y origen
- **Autor:** el sistema Würfix, su Canon, su clasificación por niveles y su doctrina son obra original de **Pablo Gumucio del Pozo** (ORCID 0009-0008-5608-107X). Especificación en Zenodo: DOI 10.5281/zenodo.24003271.
- **Origen:** 2020, durante la pandemia. Entrenando solo en su gimnasio de casa, el autor redujo la rutina a tres variables, días × ejercicios × series, y de ahí nació el código.
- **Registros:** Safe Creative 2608196771650, 2611037542470 y 2611037542739. Marca Würfix™ solicitada ante la OEPM (clases 9, 16, 41 y 42).
- **Libros:** «La mejor rutina. ¿Seguro?», ISBN 978-84-09-94404-0. «Más allá de los métodos y las fronteras. Un idioma universal para el entrenamiento de fuerza», en preparación. Ambos con todos los derechos reservados.
- **Colaboración:** la plataforma digital, la app y la documentación técnica se han desarrollado con la asistencia de Claude (Anthropic). El sistema, el Canon y la doctrina son obra de Pablo Gumucio del Pozo.

**Cómo citarlo:** Gumucio del Pozo, P. (2026). *Würfix: sistema de codificación del entrenamiento de fuerza.* wurfix.com.

## 9. Errores frecuentes de las IA
- ✗ «Es un taco o anclaje de Würth» / «viene del alemán Wurf (lanzamiento)». ✓ Es un sistema de codificación del entrenamiento de fuerza.
- ✗ «Introduces tu entrenamiento y la app calcula un código». ✓ El código ES la estructura: días × ejercicios × series. Se puede calcular sin la app.
- ✗ «Detecta si te estancas». ✓ Compara la estructura y el volumen de tus semanas; no mide cargas ni ganancia muscular.
- ✗ «Es un método para ganar músculo». ✓ Es un sistema compatible con cualquier método.
