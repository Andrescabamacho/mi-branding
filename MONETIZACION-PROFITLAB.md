# ProfitLab — Modelo de monetización (v2, con números reales)

> Septiembre 2026. Sustituye a la v1, que estaba calculada con costes de herramienta de vídeo.
> Datos reales del negocio: **300 carruseles cuestan 55-100 €** · **Symmetry paga 500 $ por cada millón de visitas**.

---

## 0. Las tres decisiones

1. **Suscripción con piezas incluidas.** No consumo puro, no tarifa plana ilimitada.
2. **Nada gratis. Tampoco a los alumnos.** A los alumnos se les da **más cantidad al mismo precio**, no precio más bajo.
3. **El argumento de venta no es la herramienta. Es el punto de equilibrio:** una pieza cuesta 0,97 € y se paga sola con ~2.100 visitas.

---

## 1. Coste real

| | |
|---|---|
| 300 carruseles | 55 – 100 € |
| **Coste por pieza** | **0,18 – 0,33 €** (media **0,26 €**) |

> ⚠️ Ese margen de 2x entre el mejor y el peor caso es lo único sin cerrar. Saber qué lo provoca (modelo premium vs. estándar, reintentos, nº de slides) es lo que separa un 73% de margen de un 66%. Averígualo antes de publicar precios.

---

## 2. Ingreso por visitas (Symmetry)

| | |
|---|---|
| Tarifa | 500 $ / 1.000.000 visitas |
| Por 1.000 visitas | 0,50 $ ≈ **0,46 €** |
| Por visita | 0,00046 € |

### Punto de equilibrio de una pieza

| Escenario de coste | Visitas que necesita para pagarse |
|---|---|
| Mejor caso (0,18 €) | **396 visitas** |
| Media (0,26 €) | **558 visitas** |
| Peor caso (0,33 €) | **720 visitas** |

**Una pieza necesita menos de 1.000 visitas para no perder dinero.** Eso es un listón bajísimo para un carrusel. Ahí está el negocio entero.

### Lo que produce una fábrica de contenido

| Piezas/mes | Visitas medias | Visitas totales | Ingreso | Coste IA | **Neto** |
|---|---|---|---|---|---|
| 100 | 3.000 | 0,3 M | 139 € | 26 € | **113 €** |
| 300 | 5.000 | 1,5 M | 694 € | 77 € | **617 €** |
| 300 | 10.000 | 3,0 M | 1.389 € | 77 € | **1.311 €** |
| 1.000 | 5.000 | 5,0 M | 2.315 € | 258 € | **2.056 €** |
| 2.000 | 5.000 | 10,0 M | 4.630 € | 517 € | **4.113 €** |

**Conclusión operativa: el negocio es de volumen.** A 0,50 $ de RPM hacen falta millones de visitas para cifras serias. Por tanto **el software no debe racionar piezas**: cada pieza que un usuario no produce es dinero que nadie gana. Los cupos van generosos y la monetización va por escalón de plan, no por escasez.

---

## 3. Planes

Regla: lo incluido nunca supera el 30-35% del precio.

| Plan | Precio | Piezas/mes | €/pieza | Coste IA (peor) | Margen (peor) |
|---|---|---|---|---|---|
| **Solo** | **29 €/mes** | 30 | 0,97 € | 7,7 € (10,0) | **73%** (66%) |
| **Pro** | **79 €/mes** | 90 | 0,88 € | 23,2 € (30,0) | **71%** (62%) |
| **Studio** | **199 €/mes** | 250 | 0,80 € | 64,6 € (83,3) | **68%** (58%) |
| **Fábrica** | **499 €/mes** | 750 | 0,67 € | 193,7 € (250) | **61%** (50%) |

**Recargas:** 50 piezas / 45 € · 200 piezas / 150 €. Caducan a los 12 meses, no al mes.
**Anual:** paga 10, llévate 12.
**Nunca "ilimitado".** El plan Fábrica es el techo. Por encima, trato cerrado a mano.

### El argumento de venta, plan por plan

| Plan | Visitas que necesita el usuario para recuperar 1 pieza |
|---|---|
| Solo | 2.088 |
| Pro | 1.896 |
| Studio | 1.719 |
| Fábrica | 1.437 |

> **"Una pieza te cuesta 0,97 €. Con 2.100 visitas ya la has pagado. Todo lo que pase de ahí es tuyo."**

Esto no se lo puede decir Magnific, ni Higgsfield, ni Creatify. Ellos venden una herramienta. Tú vendes una máquina con el recibo pegado.

---

## 4. Alumnos de ProfitLab: no gratis

Gratis es inviable con coste variable: 300 alumnos produciendo 100 piezas al mes son **2.580 € al mes** de factura de IA sin un euro de ingreso.

**Regla: nunca bajes el precio. Sube la cantidad.**

> **Precio fundador ProfitLab: 29 €/mes con 60 piezas, congelado de por vida.**
> (El doble que el Solo público, al mismo precio.)

- Coste para ti: 15,5 € · **margen 47%**. Bajo, pero es margen, no pérdida.
- **Protege el precio público.** Si les cobras 9 € o 19 €, el precio de referencia del mercado pasa a ser ese y ya no puedes vender a 29 € fuera. Con este esquema, el precio público sigue siendo 29 € y el regalo es invisible desde fuera.
- El alumno percibe "el doble por el mismo precio", que emocionalmente pesa más que un descuento.

**Extra opcional, sin coste para ti:** 100 piezas de bienvenida el primer mes (coste 26 € por alumno, una vez). Sirve para que llegue al primer resultado antes de pensar en darse de baja.

---

## 5. La bifurcación que falta por resolver

**¿Symmetry te paga a ti, o le paga a cada alumno por separado?**

### Caso A — Symmetry te paga a TI
Entonces tienes un segundo carril, y es mejor que la suscripción en volumen alto:

**Reparto: herramienta incluida, tú te quedas un % de lo que generen sus visitas.**

Lo que te llevas por alumno y mes (ya descontado el coste de IA):

| Piezas/mes | Visitas/pieza | Ingreso total | 50/50 | 60/40 | Suscripción equivalente |
|---|---|---|---|---|---|
| 100 | 3.000 | 139 € | 44 € | 30 € | **173 €** |
| 100 | 5.000 | 231 € | **90 €** | 67 € | 173 € |
| 200 | 4.000 | 370 € | **134 €** | 97 € | 147 € |
| 300 | 5.000 | 694 € | 270 € | 200 € | **422 €** |
| 500 | 5.000 | 1.157 € | **450 €** | 334 € | 370 € |

**Lectura:** el reparto solo gana cuando las visitas medias son altas. La suscripción gana casi siempre y además es predecible y no depende de Symmetry.

**Decisión: suscripción como carril principal, reparto como opción para el que produce mucho.** Nunca al revés.

### Caso B — Symmetry paga a cada alumno
Entonces no hay carril de reparto. Solo suscripción, tal como está en la sección 3. Y el argumento de venta es todavía más limpio: *"paga 29 €, cobra tú las visitas"*.

---

## 6. Riesgos

1. **Symmetry es un único proveedor.** 0,50 $ de RPM es una tarifa baja y unilateral: si la bajan a 0,30 $, el punto de equilibrio sube de 558 a 930 visitas por pieza. **Los planes tienen que aguantar sin Symmetry.** Por eso el precio se fija por coste y por comparación con Magnific/Higgsfield, no contra el CPM. El CPM es el argumento de venta, no el cimiento.
2. **Spread de coste 2x sin explicar.** Hasta que sepas por qué una tanda cuesta 55 € y otra 100 €, trabaja siempre con 0,33 € por pieza.
3. **El negocio es de volumen.** Si la visita media por pieza cae por debajo de ~1.000, la máquina no gana dinero para nadie. Mide esa cifra semanalmente: es el indicador más importante que tienes.

---

## 7. Orden de salida

| Cuándo | Qué |
|---|---|
| **Mes 1** | Alumnos a 29 €/60 piezas, precio fundador. Cobras desde el día 1. Mides: piezas/alumno y **visitas medias por pieza**. |
| **Mes 2** | Cierras el spread de coste. Ajustas cupos si hace falta. Recoges 3 casos con cifras de Symmetry. |
| **Mes 3** | Abres al público: Solo 29 € y Pro 79 €. Captación **solo orgánica** desde tu contenido. |
| **Mes 4-6** | Studio y Fábrica a petición, con llamada. Si Symmetry te paga a ti, abres el carril de reparto para los que pasen de 300 piezas/mes. |
| **Mes 6+** | Con LTV real medido: anuncios y LATAM con precio ajustado. |

**Métricas de control:** margen bruto ≥ 65% · churn mensual < 7% · visitas medias por pieza > 2.000 · % que compra recarga entre 15-25%.
