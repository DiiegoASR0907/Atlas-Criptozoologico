# v2.7 — AUDITORÍA MAESTRA DEL ATLAS

**Estado:** Documento de control de calidad previo a Canva  
**Alcance:** Volumen I — América  
**Expedientes auditados:** 20  
**Regla de proceso:** Investigación → Documento → GitHub → Verificación → Auditoría → Correcciones → Canva

> **Principio rector:** No inventar para llenar páginas. Documentar primero; diseñar después.

---

## 1. Propósito

Esta auditoría consolida el estado documental del bloque principal del Atlas antes de iniciar la maquetación en Canva. No modifica todavía los expedientes individuales. Su función es detectar inconsistencias, duplicaciones, vacíos, diferencias metodológicas y necesidades de investigación adicional.

La auditoría debe considerarse un documento de control, no una nueva fuente primaria. Cuando una conclusión no está respaldada por el material auditado, se marca como pendiente de verificación.

---

## 2. Inventario definitivo de los 20 expedientes

| Nº | Código | Expediente | Bloque | Estado preliminar |
|---:|---|---|---|---|
| 01 | AM-HOM-001 | Bigfoot (Sasquatch) | Humanoides | Revisión IIIC |
| 02 | AM-HOM-002 | Yeti americano (Alma) | Humanoides | Revisión crítica / R1 |
| 03 | AM-HOM-003 | Mapinguarí | Humanoides | Revisión IIIC |
| 04 | AM-HOM-004 | Skunk Ape | Humanoides | Revisión IIIC |
| 05 | AM-DEP-001 | Chupacabras | Depredadores | Revisión IIIC |
| 06 | AM-DEP-002 | Beast of Bray Road | Depredadores | Revisión IIIC |
| 07 | AM-DEP-003 | Cadborosaurus terrestre / reportes costeros | Depredadores | **Duplicación/alcance por resolver** |
| 08 | AM-LAC-001 | Ogopogo | Lacustres | Revisión IIIC |
| 09 | AM-LAC-002 | Champ | Lacustres | Revisión IIIC |
| 10 | AM-LAC-003 | Nahuelito | Lacustres | **Ampliación documental recomendada** |
| 11 | AM-VOL-001 | Mothman | Voladores | Revisión IIIC |
| 12 | AM-VOL-002 | Thunderbird | Voladores | Revisión IIIC |
| 13 | AM-MAR-001 | Lusca | Marinas | Revisión IIIC |
| 14 | AM-MAR-002 | Caddy (Cadborosaurus) | Marinas | **Cruce con AM-DEP-003** |
| 15 | AM-ESP-001 | Jersey Devil | Casos especiales | Revisión IIIC |
| 16 | AM-ESP-002 | Dover Demon | Casos especiales | Revisión IIIC |
| 17 | AM-ESP-003 | Flatwoods Monster | Casos especiales | Revisión IIIC |
| 18 | AM-ESP-004 | Fouke Monster | Casos especiales | Revisión IIIC |
| 19 | AM-ESP-005 | Enfield Horror | Casos especiales | Revisión IIIC |
| 20 | AM-ESP-006 | Goatman | Casos especiales | Revisión IIIC |

**Nota:** el inventario conserva los 20 expedientes del manuscrito base. Esta auditoría no elimina ni renumera expedientes.

---

## 3. Matriz de códigos

### 3.1 Estructura

- `AM-HOM` = Humanoides
- `AM-DEP` = Depredadores
- `AM-LAC` = Lacustres
- `AM-VOL` = Voladores
- `AM-MAR` = Marinas
- `AM-ESP` = Casos especiales

### 3.2 Control

La secuencia numérica es coherente como inventario de 20 expedientes. El principal problema no es la numeración sino la clasificación temática de Cadborosaurus: AM-DEP-003 y AM-MAR-002 se refieren a material estrechamente relacionado.

**Acción:** conservar ambos códigos provisionalmente y resolver mediante una nota de relación documental antes de Canva.

---

## 4. Matriz IIIC — estado de auditoría

| Código | Nivel usado en documentación | Nivel según arquitectura v0.4 | Observación |
|---|---|---|---|
| AM-HOM-001 | III | III | Revisar definición aplicada |
| AM-HOM-002 | IV | IV | Revisar porque el expediente es principalmente externo/folclórico y geográficamente problemático |
| AM-HOM-003 | III | III | Revisar evidencia dominante |
| AM-HOM-004 | III | III | Revisar evidencia dominante |
| AM-DEP-001 | III | III | Revisar evidencia dominante |
| AM-DEP-002 | III | III | Revisar evidencia dominante |
| AM-DEP-003 | III | III | Resolver relación con Caddy |
| AM-LAC-001 | III | III | Revisar evidencia dominante |
| AM-LAC-002 | III | III | Revisar evidencia dominante |
| AM-LAC-003 | III | III | Ampliación documental recomendada |
| AM-VOL-001 | III | III | Revisar evidencia dominante |
| AM-VOL-002 | III | III | Revisar evidencia dominante |
| AM-MAR-001 | III | III | Revisar evidencia dominante |
| AM-MAR-002 | III | III | Resolver relación con AM-DEP-003 |
| AM-ESP-001 | III | III | Revisar evidencia dominante |
| AM-ESP-002 | III | III | Revisar evidencia dominante |
| AM-ESP-003 | III | III | Revisar evidencia dominante |
| AM-ESP-004 | III | III | Revisar evidencia dominante |
| AM-ESP-005 | III | III | Revisar evidencia dominante |
| AM-ESP-006 | V | V | Coherente con enfoque folclórico |

> **Advertencia:** esta matriz no constituye todavía una recategorización definitiva. La discrepancia detectada es principalmente terminológica: varios expedientes utilizan “Nivel III — múltiples testimonios consistentes”, mientras que la arquitectura metodológica v0.4 define Nivel III como “evidencia documental”. Debe aprobarse una única definición antes de congelar los sellos IIIC.

---

## 5. Reconciliación del sistema I–V

### Definición maestra actualmente documentada en v0.4

**Nivel I — Evidencia científica sólida**  
Evidencia biológica o científica fuerte y verificable.

**Nivel II — Evidencia física parcial**  
Restos, muestras, huellas u otros elementos físicos relevantes, pero insuficientes para confirmar una entidad.

**Nivel III — Evidencia documental**  
Casos con documentación histórica/testimonial/visual considerable, pero sin confirmación biológica definitiva.

**Nivel IV — Testimonios consistentes**  
Múltiples testimonios relativamente coherentes sin suficiente evidencia física/documental para subir de categoría.

**Nivel V — Folclore y leyenda**  
Casos sustentados principalmente por tradición, mito, leyenda o construcción cultural sin evidencia verificable.

### Regla de reconciliación

Hasta que se apruebe una modificación formal de v0.4, **v0.4 es la referencia metodológica maestra**. No se cambiarán silenciosamente las definiciones dentro de los expedientes.

---

## 6. Detección de duplicados y cruces

### 6.1 Cadborosaurus

**AM-DEP-003** y **AM-MAR-002** presentan una relación documental directa.

No se debe contabilizar el mismo testimonio como dos evidencias independientes.

**Acción propuesta:** mantener ambos expedientes por fidelidad al manuscrito base, pero incorporar una relación cruzada explícita y un inventario de testimonios compartidos.

### 6.2 Alma

AM-HOM-002 conserva una identidad editorial heredada del manuscrito base (“Yeti americano / Alma”), pero la investigación externa utilizada para su R1 indica que Almas/Alma pertenece principalmente a tradiciones de Eurasia. Esto requiere una nota editorial clara antes de maquetar.

### 6.3 Versiones históricas

Los archivos R1 y otras variantes de una misma versión se consideran **estados de trabajo**, no capítulos adicionales del libro. Canva deberá consumir únicamente archivos marcados como definitivos/aprobados.

---

## 7. Estado documental por expediente

### Verde — documentalmente encaminado

Bigfoot, Mapinguarí, Skunk Ape, Chupacabras, Beast of Bray Road, Ogopogo, Champ, Mothman, Thunderbird, Lusca, Jersey Devil, Dover Demon, Flatwoods Monster, Fouke Monster, Enfield Horror y Goatman.

**Nota:** “Verde” significa que existe una estructura documental suficiente para continuar la revisión; no significa que el expediente esté aprobado automáticamente para Canva.

### Amarillo — requiere ampliación o aclaración

- **AM-HOM-002 Alma:** aclaración geográfica/editorial.
- **AM-LAC-003 Nahuelito:** ampliar fuentes primarias/secundarias y procedencia de evidencias visuales.
- **AM-VOL-002 Thunderbird:** revisar consistencia de fuentes y separación entre tradición indígena y criptozoología moderna.
- **AM-MAR-001 Lusca:** reforzar fuentes históricas y separar pulpo gigante/folclore de evidencia zoológica.

### Rojo — requiere decisión antes de Canva

- **AM-DEP-003 / AM-MAR-002:** relación Cadborosaurus/Caddy.
- **Sistema IIIC:** definición única de niveles.

---

## 8. Jerarquía de fuentes

El Atlas adoptará la siguiente clasificación interna:

**S1 — Fuente primaria**  
Documento original, archivo, periódico contemporáneo, entrevista/testimonio original, registro institucional primario.

**S2 — Fuente académica**  
Artículo revisado por pares, libro académico, universidad, archivo académico o investigación especializada.

**S3 — Fuente institucional**  
Museo, gobierno, parque, organismo histórico, biblioteca o institución cultural.

**S4 — Fuente secundaria especializada**  
Investigador, sociedad folklórica, obra especializada o publicación de divulgación experta.

**S5 — Fuente popular**  
Prensa secundaria, blogs, turismo, Wikipedia, redes sociales o contenido de entretenimiento.

### Regla

Una fuente S4/S5 puede documentar la existencia de una afirmación o tradición, pero **no convierte por sí sola esa afirmación en evidencia zoológica**.

---

## 9. Bibliografía maestra — estructura

La bibliografía maestra definitiva debe consolidar, sin duplicar entradas, las fuentes usadas por los 20 expedientes.

### Categorías que deben integrarse

1. Manuscrito base del Atlas.
2. Fuentes primarias históricas.
3. Archivos universitarios e institucionales.
4. Artículos académicos.
5. Libros especializados.
6. Prensa histórica.
7. Sociedades folklóricas.
8. Fuentes de investigación criptozoológica.
9. Fuentes culturales/folclóricas.
10. Fuentes web secundarias.

**Estado:** la bibliografía maestra completa queda pendiente de normalización expediente por expediente. No se inventarán datos bibliográficos faltantes.

---

## 10. Vacíos de investigación

| Prioridad | Expediente / tema | Vacío |
|---|---|---|
| Alta | Sistema IIIC | Reconciliar definiciones con uso real |
| Alta | Cadborosaurus | Separar evidencia compartida entre AM-DEP-003 y AM-MAR-002 |
| Alta | Alma | Confirmar y redactar nota sobre procedencia geográfica |
| Media | Nahuelito | Profundizar fuentes y procedencia de imágenes/videos |
| Media | Thunderbird | Diferenciar tradición cultural de criptozoología moderna |
| Media | Lusca | Reforzar historia documental y evidencia biológica |
| Media | Bibliografía maestra | Normalizar autores, títulos, fechas, instituciones y URLs |
| Baja | Expedientes restantes | Control uniforme de procedencia de cada evidencia |

---

## 11. Expedientes que requieren R1/R2

### R1 — Revisión documental prioritaria

- AM-HOM-002 — Alma
- AM-LAC-003 — Nahuelito
- AM-VOL-002 — Thunderbird
- AM-MAR-001 — Lusca

### R2 — Reconciliación editorial

- AM-DEP-003 — Cadborosaurus terrestre/reportes costeros
- AM-MAR-002 — Caddy/Cadborosaurus
- Todos los expedientes afectados por la definición final del IIIC

**Regla:** R1/R2 no implica que el expediente sea descartado; implica que todavía no está congelado para diseño.

---

## 12. Expedientes aprobados para Canva

**NINGUNO queda automáticamente aprobado por esta v2.7.**

La auditoría identifica preparación documental, pero la aprobación visual requiere superar el checklist final después de resolver las inconsistencias de IIIC, duplicados y bibliografía.

---

## 13. Expedientes bloqueados para Canva

Bloqueados hasta resolución:

1. AM-HOM-002 — Alma.
2. AM-LAC-003 — Nahuelito.
3. AM-VOL-002 — Thunderbird.
4. AM-MAR-001 — Lusca.
5. AM-DEP-003 — Cadborosaurus terrestre/reportes costeros.
6. AM-MAR-002 — Caddy/Cadborosaurus.
7. Cualquier expediente cuya clasificación IIIC cambie tras la reconciliación metodológica.

---

## 14. Reglas editoriales definitivas propuestas

1. **No inventar para llenar páginas.**
2. Separar hechos, testimonios, hipótesis y folclore.
3. No presentar una hipótesis como hecho.
4. No contar el mismo testimonio como evidencia independiente en expedientes duplicados.
5. Una fuente secundaria demuestra que una afirmación existe; no necesariamente que sea verdadera.
6. No atribuir especie, ADN, anatomía o comportamiento sin evidencia.
7. Las imágenes reconstruidas deben etiquetarse como reconstrucciones.
8. Las fotografías históricas deben conservar procedencia.
9. Los mapas deben distinguir localización de reportes de distribución biológica.
10. Las fuentes deben normalizarse antes de Canva.
11. Las versiones R1/R2 son estados de trabajo y no páginas del libro.
12. Canva no puede utilizar contenido documental pendiente de aprobación.
13. La clasificación IIIC debe utilizar una única definición maestra.
14. Cuando el manuscrito base y la investigación externa entren en conflicto, se debe señalar explícitamente el conflicto.
15. Ningún expediente se modifica silenciosamente: las correcciones importantes deben quedar registradas en su historial editorial.

---

## 15. Checklist — “DOCUMENTALMENTE LISTO PARA CANVA”

Un expediente solamente recibe el sello **DOCUMENTALMENTE LISTO PARA CANVA** cuando cumple todos los puntos:

- [ ] Código definitivo confirmado.
- [ ] Nombre definitivo confirmado.
- [ ] Bloque/categoría confirmado.
- [ ] No existe duplicación no resuelta.
- [ ] Resumen revisado.
- [ ] Ficha técnica revisada.
- [ ] Cronología revisada.
- [ ] Testimonios separados de hechos documentales.
- [ ] Evidencias clasificadas por tipo.
- [ ] Fotografías/videos con procedencia identificada o marcados como no verificables.
- [ ] Hipótesis claramente separadas.
- [ ] Cultura popular separada de evidencia.
- [ ] Evaluación IIIC aplicada según definición maestra.
- [ ] Dictamen revisado.
- [ ] Fuentes verificadas.
- [ ] Bibliografía normalizada.
- [ ] Vacíos críticos cerrados o expresamente declarados.
- [ ] Espacios visuales definidos.
- [ ] Texto final congelado.
- [ ] Archivo marcado como **FINAL / CANVA READY**.

---

## 16. Decisión de cierre de v2.7

La auditoría **NO autoriza todavía el inicio general de Canva**.

El proyecto pasa a una fase intermedia:

**v2.7 Auditoría → R1/R2 de expedientes prioritarios → reconciliación IIIC → bibliografía maestra → aprobación individual → Canva.**

La razón no es falta de contenido, sino la necesidad de mantener consistencia metodológica y evitar que una inconsistencia documental se convierta en un problema de diseño.

---

## 17. Registro de control

**Versión:** v2.7  
**Tipo:** Auditoría maestra  
**Alcance:** 20 expedientes  
**Canva:** BLOQUEADO  
**Siguiente fase:** correcciones R1/R2 y matriz de aprobación
