# ProfitLab — Modelo de monetización y análisis de mercado

> Documento de decisión. Septiembre 2026.
> Pregunta que responde: ¿suscripción o consumo por API? ¿Y a qué público amplío después de los alumnos de ProfitLab?

---

## 0. Respuesta corta

**Ni suscripción pura ni consumo puro. Híbrido: cuota mensual base + bolsa de usos incluida + recargas opcionales.**

Y con un matiz que importa más que el modelo de precios:

**Para el alumno de ProfitLab, el software NO se vende aparte. Va dentro del programa.**
**La suscripción suelta se vende al que YA tiene al menos un cliente pagando.**

Son dos negocios distintos con dos motores de retención distintos. Mezclarlos es el error caro.

---

## 1. Por qué no suscripción plana (todo incluido)

Tu software consume inferencia de IA. Eso es coste variable real por cada clic: cada imagen, cada upscale, cada vídeo te cuesta dinero aunque el usuario pague lo mismo.

Con tarifa plana pasan tres cosas, siempre, en este orden:

1. El 5-10% de usuarios intensivos consume el 60-80% de tu factura de IA.
2. Tu margen bruto se hunde. Los datos de 2026: los que meten la IA dentro de la suscripción sin techo acaban en **60-75% de margen** *si controlan el consumo*; los que no lo controlan bajan de ahí rápido. El margen medio de producto IA está en **~50%**, muy por debajo del 70-80% clásico de SaaS.
3. Para no perder dinero subes el precio a todos. Y matas al principiante, que es tu público.

La tarifa plana solo funciona cuando el coste marginal es ~0. El tuyo no lo es.

---

## 2. Por qué no consumo puro (pay-per-use / API)

Este es el error que parece "justo" y es el que más te costaría.

**Tu público son personas que empiezan de cero.** Un principiante necesita *fallar mucho*: generar 40 versiones, tirar 35, quedarse con 5. Ese es literalmente el proceso de aprender.

Si cada generación descuenta saldo visible:

- **Se paraliza.** Piensa antes de cada clic. Genera menos. No practica.
- **No llega al momento "ah, funciona".** El 90% de los que se van en la primera semana nunca entendieron el valor del producto. Cobrar por intentar es la forma más eficiente de impedir que lo entiendan.
- **No consigue su primer cliente.** Y si no consigue cliente, no hay testimonio, no hay caso de éxito, no hay boca a boca. Se te cae el motor de crecimiento entero.
- **Ansiedad de factura.** El 78% de responsables de compra reportan cargos inesperados en facturas ligadas a consumo. Introducir medición de IA sube la fuga mensual **+1,5 puntos porcentuales** en los primeros 6 meses; los modelos de suscripción con uplift quedan neutros o mejor.

Y hay un problema de negocio aún mayor: **el consumo puro no te da ingreso recurrente predecible**. Agosto existe. Las vacaciones existen. El alumno que se desmotiva tres semanas te factura 0€ y no se da de baja, así que ni siquiera te enteras de que lo has perdido.

El consumo puro solo tiene sentido en un caso, y lo dejas para después: **una API de ProfitLab para agencias/desarrolladores con volumen irregular** (fase 3, año 2).

---

## 3. Qué hace el mercado (datos, no opiniones)

### 3.1 Adopción del modelo híbrido

| Modelo | Hace 12 meses | Hoy | Previsión fin 2026 |
|---|---|---|---|
| Híbrido (base + uso) | 27% | **41%** | **61%** |
| Por asiento/usuario | 21% | 15% | ↓ |
| Tarifa plana | 29% | 22% | ↓ |

- Las empresas con **solo asientos** tienen **2,3x más churn** que las híbridas o de consumo.
- Las de facturación híbrida crecen a una **mediana del 21%**, por encima tanto de suscripción pura como de consumo puro.
- Gartner: **70% de las empresas preferirán modelos por uso** frente a por asiento en 2026.

**El híbrido ha ganado. No es una opinión de mercado, es el estándar.**

### 3.2 Qué cobran tus competidores/vecinos (USD/mes, 2026)

| Herramienta | Entrada | Medio | Alto | Nota |
|---|---|---|---|---|
| **Magnific / Freepik** | $16 ($11 anual) | $37 ($27,5) | $90 ($66,9) | Desde abril 2026 Magnific es Freepik: una sola marca, un solo sistema de créditos. **Bolsa anual, sin reseteo mensual.** |
| **Higgsfield** | $19 (270 cr) | $47-59 (1.200 cr) | $99-129 (3.000 cr) | |
| **Creatify** | gratis (10 cr) | $39 (100 cr) | $99 (300 cr) | |
| **Arcads** | $110 (10 vídeos) | $220 (20 vídeos) | — | ~$11 por vídeo |
| **AdCreative.ai** | ~$39 | — | — | |

**Lecturas:**

1. **La banda de entrada del mercado creador está en $16-39/mes.** Tu precio de entrada tiene que vivir ahí o debajo. En euros: **29€**.
2. **Todos usan créditos.** Ninguno cobra tarifa plana ilimitada. Los que más saben de este negocio ya descartaron las dos opciones extremas.
3. **Magnific hace algo muy inteligente que deberías copiar: bolsa anual, no mensual.** Un mes flojo financia un mes fuerte. Eso elimina la mitad de la ansiedad del principiante y reduce bajas por "este mes no lo he usado".
4. **Arcads cobra $11 por vídeo y vive.** Cuando el output es claramente vendible, el mercado paga por unidad. Pero su cliente es una agencia de performance, no alguien que empieza.

---

## 4. La regla que decide tus precios: 30/70

No fijes el precio mirando a la competencia. Fíjalo desde el coste y valídalo contra la competencia.

**Regla: lo que incluyes en el plan no puede costarte más del 30% del precio del plan.**

Eso te deja en ~70% de margen bruto, que es la zona sana para un producto IA.

| Plan | PVP | Presupuesto máx. de coste IA incluido | Margen objetivo |
|---|---|---|---|
| Solo | 29 €/mes | ≤ 8,50 € | ~70% |
| Pro | 79 €/mes | ≤ 23 € | ~71% |
| Studio | 199 €/mes | ≤ 58 € | ~71% |

**Las recargas se venden a 3,5-4x tu coste.** Ahí es donde recuperas margen del usuario intensivo sin castigar al normal.

> **Dato que necesito de ti para cerrar los números:** el coste real por operación en tu stack (imagen, upscale, vídeo de 5s, texto). Órdenes de magnitud habituales en 2026: imagen estándar 0,01-0,04 €, imagen premium 0,05-0,15 €, upscale 0,05-0,20 €, vídeo corto 0,15-1,50 €. Con tus cifras reales convierto el presupuesto de coste en número exacto de "creaciones" por plan.

---

## 5. Estructura recomendada

### 5.1 La métrica de valor: NO vendas créditos, vende clientes

Este es el punto más importante del documento.

Tu usuario no gana dinero por generar imágenes. Gana dinero **por cada empresa a la que le lleva el contenido**. En España eso son **300-800 €/mes por cliente** (freelance) o **500-1.500 €/mes** (agencia).

Entonces tu precio debe escalar con **el número de marcas/clientes activos**, no con tokens. Dos ejes:

- **Eje 1 — Marcas activas:** lo que define el plan. Es lo que crece cuando el usuario gana más. Es lo que hace que subir de plan se sienta como un ascenso, no como un peaje.
- **Eje 2 — Creaciones incluidas:** lo que protege tu margen. Con recargas para quien se pase.

Si un usuario cobra 400 €/mes a una peluquería y te paga 29 €, eso es un **7% de su facturación por cliente**. Indiscutible. Si le cobras por token, cada generación le recuerda que está gastando. Si le cobras por cliente, cada cobro le recuerda que está ganando.

### 5.2 Planes

| | **ProfitLab** | **Solo** | **Pro** | **Studio** |
|---|---|---|---|---|
| Precio | Incluido en el programa | **29 €/mes** | **79 €/mes** | **199 €/mes** |
| Anual | — | 290 € (2 meses gratis) | 790 € | 1.990 € |
| Marcas activas | 2 | 2 | 8 | 25 |
| Creaciones/mes | Bolsa de bienvenida | X | ~4X | ~12X |
| Usuarios | 1 | 1 | 1 | 5 |
| Marca blanca / entrega a cliente | — | — | ✅ | ✅ |
| Aprobaciones del cliente | — | — | ✅ | ✅ |
| Soporte | Comunidad | Comunidad | Email | Prioritario |

**Recargas:** 10 € / 25 € / 50 €. **Caducidad 12 meses, no mensual.** (Copiado de Magnific, y es correcto.)

**Bolsa acumulable:** lo no usado se arrastra hasta un tope de 2x el cupo mensual. Esto solo te cuesta si lo gastan, y elimina la sensación de "pago por nada".

### 5.3 Mensual vs anual

- El mensual convierte **25-35% mejor**, pero sube el churn **8-12%**.
- El anual te paga por adelantado la inferencia que vas a consumir. Con costes variables, eso es caja que necesitas.

**Decisión: ofrece los dos, empuja el anual con 2 meses gratis.** No hagas solo anual: tu público empieza de cero y no suelta 290 € de golpe sin haber cobrado su primer cliente.

---

## 6. Fase 0 — Los alumnos de ProfitLab

Tienes un activo que el 99% de los SaaS no tiene: **usuarios calientes, con contexto, a coste de adquisición cero.** No lo quemes cobrándoles 29 €.

**Qué hacer:**

1. **Incluido en el programa, 12 meses.** El software deja de ser un gasto y pasa a ser la razón por la que ProfitLab vale más que la competencia. Te permite **subir el precio del programa** o justificar el que tienes.
2. **Precio fundador vitalicio al acabar esos 12 meses: 19 €/mes**, congelado. Cuesta poco y te compra la lealtad de la cohorte que va a generar todos tus testimonios.
3. **Lo que te llevas a cambio (esto es el trato, no un regalo):**
   - Datos reales de consumo → con eso calibras el cupo de cada plan **antes** de abrir al público.
   - Pruebas de carga y bugs con gente que te perdona los fallos.
   - Casos de éxito con cifras. Tu marca ya funciona con prueba ("capturas de pagos, antes/después"). Esto la alimenta.
4. **Migración de Magnific:** están pagando $16-37 ahí. Si ProfitLab cubre parte de ese flujo, el ahorro es tu argumento de venta y tu ancla de precio. Mídelo: "cuántos de los que entran cancelan o bajan de plan en Magnific" es tu métrica de encaje producto-mercado más honesta.

**Lo que NO debes hacer:** darles acceso "de por vida gratis". Coste variable de por vida = bomba de relojería. Doce meses, y luego precio fundador.

---

## 7. A quién ampliar: análisis de segmentos

Ordenados por rentabilidad real, no por tamaño.

### 🥇 Segmento 1 — Freelance con 1+ cliente pagando ("el profesionalizado")
**Este es tu cliente de pago. No el principiante absoluto.**

- **Quién es:** community manager o creador de contenido autónomo, gestiona 1-5 marcas, factura 300-800 €/mes por cliente.
- **Tamaño:** España tiene **3,3M de autónomos** y el **41% de las empresas ya trabajan con freelancers**. El subconjunto marketing/contenido está en el orden de **decenas de miles** en España; con LATAM hispanohablante, multiplica por 5-8 en volumen.
- **Disposición a pagar:** alta y racional. 29-79 € contra una facturación de 1.500-3.000 €/mes es ruido.
- **Churn:** bajo. No se da de baja de la herramienta con la que entrega a su cliente.
- **Dónde encontrarlo:** tu propio contenido en IG, y los alumnos de ProfitLab que ya facturan.

### 🥈 Segmento 2 — Micro-agencias y estudios (2-10 personas)
- **Quién es:** agencia pequeña con 5-20 marcas, factura 500-1.500 €/mes por cuenta.
- **Disposición a pagar:** **199-499 €/mes sin pestañear**, porque sustituye horas de un junior (20-35 €/h).
- **Churn:** muy bajo. Es el segmento con mejor LTV de toda la lista.
- **Coste de venta:** más alto (necesitan multi-usuario, marca blanca, aprobaciones del cliente). Por eso el plan Studio existe desde el día 1 aunque al principio no lo compre nadie.
- **Veredicto:** es donde está el dinero de verdad. Pero entra aquí en fase 2, cuando el producto aguante multi-marca.

### 🥉 Segmento 3 — Principiante absoluto (el público de ProfitLab)
- **Tamaño:** enorme. Disposición a pagar: real, pero por **transformación**, no por herramienta.
- **El problema:** su churn no depende de tu producto. Depende de **su propia motivación**. Se apunta, lo usa tres semanas, la vida se le cruza, se va. Con 29 €/mes y una vida media de 2-3 meses, el LTV es de **60-90 €**. Si lo captas con publicidad pagada (CAC 40-80 €), el negocio no sale.
- **Veredicto: NO lo ataques con suscripción suelta y publicidad pagada.** Es el público del *programa*, no del *software*. Véndele ProfitLab (formación + comunidad + herramienta dentro) y captalo con tu contenido orgánico, que es lo que ya te funciona.

### Segmento 4 — PYME directa (peluquerías, clínicas, gimnasios, restaurantes)
- **Disposición a pagar:** la más alta de todas (**300-1.000 €/mes**), pero **no quieren software, quieren el resultado**. Tres de cada cuatro marcas se mueven por debajo de 1.000 €/mes en contenido.
- **Veredicto: no es tu cliente de SaaS.** Pero sí es la demanda que da de comer a tus alumnos. La jugada inteligente no es venderles a ellos: es **conectar PYMEs con alumnos de ProfitLab**. Eso hace que tu programa se venda solo y que tus usuarios no se den de baja nunca.

### Segmento 5 — LATAM
- **Volumen:** 5-10x España. **Sensibilidad al precio: 40-60% mayor.**
- **Veredicto:** entra, pero con **precio por paridad de poder adquisitivo** (Solo a 14-19 $ en MX/CO/AR/PE). Si aplicas precio español, no convierte. Si aplicas precio LATAM en España, destruyes margen. Geoprecio o nada. **Fase 2-3.**

---

## 8. Qué NO hacer

1. **Ningún plan "ilimitado".** Nunca. Ni como gancho de lanzamiento. El usuario lo recordará para siempre y quitarlo te costará clientes.
2. **No llames "créditos" a los créditos.** Llámalos **creaciones**, **piezas** o **entregas**. Que la unidad sea algo que el usuario reconozca como valor entregado, no como combustible que se agota. Es el mismo mecanismo con la mitad de ansiedad.
3. **No enseñes el contador con números rojos.** Muestra "te quedan 180 creaciones este mes", no una barra vaciándose. La diferencia en comportamiento es enorme.
4. **No cambies precios a los que ya están dentro.** Cambiar el modelo sin proteger a los existentes cuesta un **10-15% de clientes**. Cualquier plan nuevo se aplica a los nuevos; los antiguos se quedan como están ("grandfathering") y así se lo dices.
5. **No compitas en la capa de modelo.** No puedes ganar a Freepik ni a Higgsfield en calidad de modelo ni en precio por imagen: van financiados por fondos y queman dinero. **Tu ventaja es la capa de flujo de trabajo**: el principiante que no sabe qué hacer, y al que tu software le da un resultado listo para entregar a una empresa española. Ese hueco no lo cubre ninguna de las herramientas de la tabla.
6. **No lances el precio público sin datos de consumo de los alumnos.** Un mes de datos reales vale más que este documento entero para fijar el cupo.

---

## 9. Plan de 90 días

**Días 1-30 — Alumnos, gratis, instrumentado**
- Acceso a todos los alumnos de ProfitLab.
- Mide obsesivamente: creaciones/usuario/semana, coste IA/usuario, % que llega a "primera entrega a un cliente".
- Objetivo: saber cuánto cuesta un usuario medio y uno del percentil 90.

**Días 31-60 — Fijar cupos y validar precio**
- Fija el cupo del plan Solo en el **percentil 75** de consumo (el 75% no toca la recarga nunca; el 25% te paga margen extra).
- Prueba de precio con 20-30 alumnos: "si esto no estuviera incluido, ¿lo pagarías a 29 €?". Y la buena de verdad: ábreles la recarga y mira quién compra.
- Cierra 3 casos de éxito con cifras.

**Días 61-90 — Abrir al público**
- Lanza Solo (29 €) y Pro (79 €) con captación **solo orgánica** desde tu contenido.
- Studio a puerta cerrada, por petición, con llamada.
- Publicidad pagada: **cero**, hasta que sepas el LTV real. Antes de eso, cualquier euro en ads es una apuesta a ciegas.

**Métricas de control:**

| Métrica | Umbral sano | Alarma |
|---|---|---|
| Margen bruto | ≥ 70% | < 60% → sube precio o baja cupo |
| Churn mensual (Solo) | < 7% | > 10% → problema de activación, no de precio |
| % usuarios que compran recarga | 15-25% | < 10% → cupo demasiado generoso |
| Coste IA del percentil 90 | < 50% del PVP | > 70% → necesitas límite duro |
| Tiempo hasta 1ª entrega a cliente | < 7 días | > 14 → el onboarding te está matando |

---

## 10. Resumen en una frase

> **Cuota base con creaciones incluidas y recargas sin caducidad mensual; el plan escala por número de marcas del usuario, no por tokens; regalado dentro de ProfitLab durante 12 meses para fabricar la prueba social; y cuando abras al público, apunta al freelance que ya cobra y a la micro-agencia — no al principiante absoluto, que es cliente de tu programa, no de tu software.**

---

## 11. Fuentes

- [Hybrid Pricing: The Complete Guide for SaaS and AI Companies (2026) — Flexprice](https://flexprice.io/blog/hybrid-pricing-guide)
- [The 2026 State of B2B SaaS and AI Monetization Report — Growth Unhinged](https://www.growthunhinged.com/p/the-state-of-b2b-monetization-in-2026)
- [AI SaaS Monetization in 2026: What Actually Works — Dodo Payments](https://dodopayments.com/blogs/ai-saas-monetization-2026)
- [AI SaaS Pricing Models in 2026 — Fungies.io](https://fungies.io/ai-saas-pricing-models-2026/)
- [Credit-Based Pricing for AI: How It Works, Where It Fails — Software Pricing Partners](https://softwarepricing.com/blog/credit-based-pricing-ai/)
- [Credit Based Pricing vs Usage Based Pricing — Flexprice](https://flexprice.io/blog/credit-based-pricing-vs-usage-based-pricing)
- [Magnific AI Pricing in 2026: Plans, Credits & API Costs — MyArchitectAI](https://www.myarchitectai.com/blog/magnific-ai-pricing)
- [Magnific Pricing 2026 — Per-Image USD by Plan — Scopeful](https://www.scopeful.org/tools/magnific)
- [Higgsfield pricing plans 2026 — Creatify](https://creatify.ai/blog/higgsfield-pricing-(2026)-plans-and-what-you-ll-actually-pay)
- [Arcads Pricing 2026 — Fluxnote](https://fluxnote.io/guides/arcads-pricing-2026)
- [Arcads vs Creatify vs Higgsfield vs Hyper (2026) — HyperFX](https://www.hyperfx.ai/blog/arcads-vs-creatify-vs-higgs-field-vs-hyper-2026)
- [Precios Community Manager 2026: Guía de Tarifas — Vender por Internet](https://www.venderporinternet.org/precios-y-tarifas-de-un-community-manager/)
- [Tarifas UGC España 2026 — The King of Content](https://thekingofcontent.agency/blog/tarifas-ugc-espana-precios-2026)
- [¿Cuánto cuesta un vídeo UGC en España en 2026? — HICARI](https://hicari.io/cuanto-cuesta-video-ugc-estudio-espana-2026/)
- [Modelos de Precios para SaaS en 2026 — SystemForge](https://systemforge.es/blog/modelos-precios-saas-como-definir-probar-2026/)
- [Precios por asiento en SaaS: por qué están muriendo — El Ecosistema Startup](https://ecosistemastartup.com/precios-por-asiento-en-saas-por-que-estan-muriendo/)
- [Freelance en España: guía completa 2026 — Asana](https://asana.com/es/resources/freelance)
- [Customer Churn In The Era Of AI Products — Userpilot](https://userpilot.com/blog/customer-churn/)
