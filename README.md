# Contexto de proyecto: Grupo Gastrobrío (Baena, Córdoba)

> Documento de handoff. Reúne todo el trabajo de investigación, estrategia y prototipado realizado para este proyecto, con las razones detrás de cada decisión — no solo el resultado. Pensado para dar contexto completo a un agente de código (Antigravity) que va a construir el sitio real.

---

## 1. El proyecto en una frase

Web multipágina tipo "hub" para un grupo de hostelería en Baena (Córdoba) con 4 locales — 3 restaurantes y 1 heladería —, cada uno con su propia identidad, accesibles desde un mismo dominio/paraguas de marca.

## 2. El cliente: Grupo Gastrobrío

Actualmente opera bajo el dominio **picoteobaena.com** (WordPress), que aloja las cartas de los 3 restaurantes pero con contenido desactualizado en algunos puntos (p. ej. la página "Sobre nosotros" solo menciona 2 restaurantes, aunque hay 3 activos — Guisoteo se añadió más tarde y el copy institucional no se actualizó).

### 2.1 Picoteo — el local principal

- **Posicionamiento**: tapeo/raciones informal, "cocina de vanguardia" con toque tradicional
- **Dirección**: Av. Padre Villoslada, 29, 14850 Baena, Córdoba
- **Teléfono**: 957 94 54 65
- **Horario apertura**: lunes a viernes 08:30–00:00 · sábados 13:00–00:00 · domingo cerrado
- **Horario pedidos a domicilio**: lunes a sábado, 12:00–17:00 y 20:00–00:00 · reparto propio, 1€
- **Historia**: fundado en 2010 por **Teo Espartero**, que empezó en hostelería a los 14 años en el Bar El Vasco (Albendín). Produce de temporada de una huerta propia en Albendín.
- **Identidad visual**: logo con tipografía negra gruesa y redondeada sobre verde lima neón, "Café · Bar de Tapas" / "Restaurante"
- **Precios de referencia**: entre 6€ y 22€ (ej. croquetas de txuleta madurada 12€, tarta de queso 6€)
- **Redes**: Facebook e Instagram @picoteobaena, TikTok @picoteobaena
- **Reputación**: valoración alta y sostenida en Google (5,0★ referenciado en el sitio)

### 2.2 La Nova Traviola — pizzería/burger informal

- **Posicionamiento**: pizzas, calzones, hamburguesas, bocadillos, perritos — registro fast-casual
- **Dirección**: ⚠️ **no confirmada** — nunca apareció en ninguna página del sitio actual
- **Teléfono**: 957 69 24 78
- **Horario apertura**: martes a domingo 20:00–00:00 · lunes cerrado
- **Horario pedidos a domicilio**: martes a domingo 20:00–00:00 · reparto propio
- **Identidad visual**: script dorado/marrón sobre óvalo, "La Nova Traviola · Pizzeria - Ristorante" — rótulo físico fotografiado, sin logo en archivo
- **Punto fuerte**: la carta sin gluten más completa del grupo (pizzas, hamburguesas, bocadillos y perritos en versión apta)
- **Precios de referencia**: pizzas 8,50€–10,50€, hamburguesas 4,50€–9,90€, baguettes/bocadillos 3€–6€

### 2.3 Guisoteo — gourmet/de autor

- **Posicionamiento**: el ticket más alto del grupo, brasas de carbón de coco, atún rojo, quesos de Zuheros
- **Teléfono / horario / dirección**: ⚠️ **ninguno confirmado** — la página de carta de Guisoteo nunca mostró pie con datos de contacto (a diferencia de Picoteo y Traviola)
- **Identidad visual**: rótulo grabado a fuego sobre madera, tipografía stencil rústica, "Taberna de Tapas GUISOTEO · El placer de un buen paladar · Restaurante"
- **Contenido**: es la carta más reciente del grupo (fotografía de julio de 2026), la mejor cuidada visualmente
- **Precios de referencia**: 4,50€–28€ (centro de chuletón 300g a la brasa 28€, tataki de atún rojo 14€, pulpo a la brasa con mayonesa de AOVE 19€, tabla de quesos de Zuheros 12€/16€)

### 2.4 Gelateo — heladería

- **Dirección**: C. Salvador Muñoz, 2, 14850 Baena, Córdoba
- **Teléfono**: 620 87 83 10 (dato obtenido de su ficha en GelatoMaps, directorio de terceros)
- **Sin web ni redes sociales propias documentadas** — su única presencia digital es un perfil sin reclamar en gelatomaps.com (score 62/100, "2 Bolas · Artesanal Acreditado")
- **Reputación**: 5,0/5 en Google con 27 reseñas — pese a no tener presencia digital propia
- **Horario**: solo se sabe que abre 3 días/semana y cierra los lunes; días exactos sin confirmar
- **Contenido**: cero fotografía propia, cero sabores documentados, cero copy — es el local que requiere trabajo desde cero

---

## 3. Inventario de contenido existente

Se hizo un rastreo completo de picoteobaena.com (home, 3 cartas, galería, sobre nosotros, entorno, innovación, para llevar) recopilando **más de 90 URLs de imágenes**. Resumen por local:

| Local | Fotos disponibles | Estado |
|---|---|---|
| Picoteo | ~55 (carta + galería + equipo) | Abundante pero mayoritariamente de 2018–2022, parte desfasada |
| Traviola | ~20 | Solo imágenes ilustrativas de categoría (pizza/burger genéricas), sin reportaje real del local |
| Guisoteo | ~18 | Escaso en cantidad pero el más reciente y cuidado (julio 2026) |
| Gelateo | 0 | Necesita reportaje fotográfico y contenido desde cero |

📄 Inventario completo con todas las URLs: `inventario-imagenes-picoteobaena.md`

**Nota de derechos**: las fotos de la sección "Nuestro Entorno" (turismo de la comarca: Zuheros, Torreparedones, Alhambra, Mezquita de Córdoba...) llevan créditos de terceros ("Foto Antonio Moreno", "Foto Yolanda Núñez") — no son producto propio del cliente, cuidado si se reutilizan.

---

## 4. Público objetivo (avatar)

**"El anfitrión de confianza"** — perfil principal:

- **Demografía**: núcleo duro 32–55 años (media ~40), residentes de Baena y comarca (Zuheros, Doña Mencía, Cabra, Luque, Nueva Carteya) o visitantes de fin de semana. Ticket medio 10–15€ (tapeo entre semana) a 25–35€ (ocasión especial). Segmentos secundarios: 22–35 años (más ligado a Traviola/delivery) y 45–65 años (turismo rural).
- **Deseos**: un sitio de fiar para cualquier ocasión, resolver el "no me apetece cocinar" con domicilio, no tener que ir hasta Córdoba capital para comer algo distinto, apoyar negocio local.
- **Miedos/objeciones**: que sea "para turistas y caro sin nada especial", no encontrar sitio sin reservar, alergias/intolerancias (preocupación real y recurrente), que la web tenga precios desactualizados, confusión entre las 3 marcas del grupo, algún mal día de servicio puntual.
- **Cómo busca**: "restaurantes en Baena Córdoba", "dónde comer en Baena", "pizza a domicilio Baena", "carta Picoteo Baena", "reservar mesa Baena teléfono", muchas búsquedas de proximidad desde el móvil.
- **Qué le hace elegir el grupo**: prueba social clara (5,0★), un solo nombre de confianza para cualquier ocasión, relato de producto (temporada, huerta, Teo Espartero, 15+ años), carta clara con precios y alérgenos, fotos reales y actuales (punto débil actual del grupo), facilidad de reserva sin intermediarios.

---

## 5. Investigación de keywords

Se analizaron 2 exportaciones de Google Keyword Planner (419 keywords únicas combinadas). **De esas, solo ~66 tenían intención transaccional real** — el resto era ruido: búsquedas de recetas para cocinar en casa (comparten palabras con los platos de la carta pero son otro público: "tarta de queso", "salsa bbq", "huevos rotos"), fragmentos rotos de la herramienta, y nombres de negocios competidores de Baena que Keyword Planner coló como "relacionados" (p. ej. "bodega palacios", "restaurante el carbonero" — luego confirmado que es un competidor real, ver sección 6).

### Grupos transaccionales identificados (sin duplicados)

| Grupo | Vol. mensual aprox. | Keyword principal | Página asignada |
|---|---|---|---|
| Para llevar / a domicilio | ~6.750 | `pedido a domicilio en baena` | `/para-llevar/` (única, Picoteo+Traviola) |
| Carta digital / ver carta | ~4.000 | `carta [marca] baena` | 3 páginas de carta ya existentes |
| Grupos y celebraciones | ~3.000 | `restaurante para grupos y celebraciones en baena` | **nueva** `/celebraciones-y-grupos/` |
| Reservar mesa | ~2.050 | `reservar mesa [marca] baena` | página Reservas de cada marca |
| Teléfono / contacto | ~1.600 | (se funde con Reservas) | misma página Reservas |
| Restaurante en Baena (geo genérico) | ~500 | `restaurantes en baena` | Home del hub |
| Marca + carta (navegacional) | ~200 | ya cubierto | páginas de carta existentes |

**Lógica anticanibalización aplicada**: Home no compite por "reservar mesa" (eso es de cada marca); "Grupos y celebraciones" se centraliza en una sola página del hub en vez de dejar que las 3 marcas compitan por la misma keyword; "carta digital" no necesita página nueva, solo optimización on-page de las 3 cartas existentes.

**Pendiente**: no hay ninguna keyword de heladería en los datos analizados — Gelateo necesita su propia tanda de investigación de keywords.

📄 Detalle completo con todas las keywords por grupo: `arquitectura-seo-grupo-gastrobrio.md`

---

## 6. Arquitectura del sitio

```
🏠 Home — Grupo Gastrobrío          → KW: "restaurantes en baena"
│
├── 🟡 /picoteo/
│   ├── /picoteo/carta/             → KW: "carta picoteo baena"
│   └── /picoteo/reservas/          → KW: "reservar mesa picoteo baena" + teléfono
│
├── 🍕 /traviola/
│   ├── /traviola/carta/            → KW: "carta traviola baena"
│   └── /traviola/reservas/         → KW: "reservar mesa traviola baena" + teléfono
│
├── 🍖 /guisoteo/
│   ├── /guisoteo/carta/            → KW: "carta guisoteo baena"
│   └── /guisoteo/reservas/         → KW: "reservar mesa guisoteo baena" + teléfono
│
├── 🍦 /gelateo/
│   ├── /gelateo/sabores/
│   └── /gelateo/como-llegar/
│   (pendiente: keyword research propio, cero datos por ahora)
│
├── 🎉 /celebraciones-y-grupos/      → KW: "restaurante para grupos y celebraciones en baena"
│      (página central, presenta Picoteo/Traviola/Guisoteo según ocasión, deriva a reservas)
│
├── 🛵 /para-llevar/                 → KW: "pedido a domicilio en baena" (cubre Picoteo + Traviola)
│
├── 📸 /galeria/
├── 👥 /sobre-nosotros/              (historia, Teo Espartero, equipo)
├── 🌍 /nuestro-entorno/             (turismo Baena/comarca)
└── ☎️ /contacto/                    (genérico grupo)
```

---

## 7. Análisis de competencia (para la keyword "restaurante en Baena")

**Competidor 1 — Bodega Palacios / Restaurante El Carbonero (bodegapalacios.es)**
✅ Segmenta por ocasión (Celebraciones/Reservas/Experiencias), CTA de reserva online visible, tour virtual 360°.
❌ Ningún encabezado usa una keyword real de búsqueda (todo es "esencia gastronómica", lenguaje de marca vacío). Carta oculta tras un sistema externo con QR. Sin horarios, dirección ni reseñas en el home. Sin FAQ.

**Competidor 2 — picoteobaena.com/la-carta/ (la propia web actual del cliente)**
✅ Contenido de producto real y actualizado, precios y alérgenos por plato.
❌ Es una página de carta, no está diseñada para competir por "restaurante en Baena" — no responde a esa intención de decisión. H2 "Alérgenos" repetido 6+ veces sin diferenciarse. Salto de jerarquía de H2 a H5 sin H3/H4. Sin argumentos de "por qué elegirnos", reseñas ni CTA de reserva.

**Conclusión**: ninguno de los dos responde bien a la intención real de "restaurante en Baena" — ahí está la oportunidad.

⚠️ Nota: el usuario mencionó "los 3 primeros resultados" pero solo proporcionó 2 URLs — el tercero queda pendiente si se quiere completar el análisis.

---

## 8. Jerarquía de encabezados definida (Home)

**H1**: Restaurante en Baena: Grupo Gastrobrío — Picoteo, Traviola y Guisoteo

**H2** → **H3** (resumen):
1. ¿Qué restaurante en Baena eliges según el plan? → H3 por cada marca (Picoteo/Traviola/Guisoteo/Gelateo)
2. Reservar mesa y horarios → H3 por cada marca con reservas/teléfono
3. Ver la carta de cada restaurante → H3 por cada carta
4. Pedido a domicilio en Baena
5. Por qué elegir Grupo Gastrobrío → H3: producto de temporada, 15+ años de trayectoria, alérgenos marcados
6. Opiniones de nuestros clientes
7. Dónde estamos y cómo llegar
8. Preguntas frecuentes sobre nuestros restaurantes en Baena

---

## 9. Copy completo de la página Home

Redactado siguiendo la jerarquía anterior, tono cercano-profesional, sin relleno genérico — cada frase apoyada en datos reales del negocio (nunca inventados). Incluye:
- Selector de plan por marca
- Bloques de reservas/horario con teléfonos reales
- Preview de las 3 cartas con platos y precios reales
- Proceso de pedido a domicilio en 4 pasos (reutilizando el proceso que ya tiene el cliente en su web actual)
- 3 argumentos de diferenciación con hechos verificables
- Espacio reservado para testimonios reales (no se inventaron citas por temas de derechos de autor)
- Huecos marcados con 🔲 en Guisoteo (teléfono/horario) y Traviola (dirección)

📄 Copy completo: `copy-home-restaurante-en-baena.md`

---

## 10. Contenido GEO (FAQ para citación por LLMs)

Se redactó un bloque de 10 preguntas frecuentes optimizado para que asistentes tipo ChatGPT puedan citar la página, con:
- Preguntas formuladas como se le preguntaría a una IA (no como keywords de Google)
- Respuestas autocontenidas (sin "como vimos arriba"), con datos concretos (teléfonos, precios, horarios) en vez de adjetivos vagos
- Recomendación de marcado `FAQPage` (schema.org) — **ya implementado** en el prototipo HTML (ver sección 11)

Las 10 preguntas cubren: mejor restaurante en Baena, opciones sin gluten, grupos grandes, pedidos a domicilio, cena especial/cumpleaños, dónde tapear, precio medio, heladería, días de cierre, reserva por teléfono.

---

## 11. Prototipo HTML

Archivo único autocontenido (HTML+CSS+JS vanilla, sin dependencias externas salvo Google Fonts), listo para abrir directamente en navegador.

📄 Archivo: `restaurante-en-baena.html`

### Sistema de diseño

- **Color**: `--ink:#1c1613` (negro-ember cálido) · `--cream:#f6efe1` · `--paprika:#bf4a28` (acento primario/CTA) · `--olive:#8f7530` (acento secundario, referencia a la DO de aceite de oliva de Baena) · `--olive-light:#c9ac5c`
- **Tipografía**: Bricolage Grotesque (titulares, carácter tosco/artesanal — conecta con los rótulos pintados a mano de Picoteo/Guisoteo) + Fraunces itálica (descripciones de platos y testimonios) + Inter (cuerpo)
- **Elemento firma**: selector interactivo "¿Dónde te apetece hoy?" — porta la interacción de flecha-deslizante del componente `menu-vertical.tsx` que aportó el cliente, con panel de foto que reacciona al hover/tap, para que sea la herramienta real de decisión rápida

### Componentes construidos

1. **Header** sticky con nav + CTA de llamada, colapsa a menú hamburguesa en móvil
2. **Hero** con imagen real de fondo (Picoteo), headline con la keyword objetivo, CTAs primario/secundario, stats (desde 2010 · 4 locales · 5,0★)
3. **Selector de local** (elemento firma) — 4 filas interactivas con preview de foto
4. **Reservas y horarios** — 3 tarjetas con teléfonos reales y huecos marcados donde falta info
5. **Carrusel 3D de carta** — puerto en JS vanilla del componente coverflow que aportó el cliente, con 8 platos reales (nombre, precio, foto) de las 3 cartas, swipe táctil, autoplay pausable, respeta `prefers-reduced-motion`
6. **Pedido a domicilio** — proceso en 4 pasos (numeración justificada: es una secuencia real, no decorativa)
7. **Por qué elegirnos** — 3 argumentos con hechos, no adjetivos
8. **Opiniones** — testimonios parafraseados (no copiados literalmente, por derechos de autor) con nombres reales ya públicos en la web del cliente
9. **Ubicación** — 4 tarjetas con direcciones (huecos marcados donde falta)
10. **FAQ** — acordeón nativo `<details>/<summary>` (accesible sin JS) + JSON-LD `FAQPage` schema ya insertado en el `<head>`
11. **Footer**

### Notas técnicas

- Las imágenes de Picoteo/Traviola/Guisoteo están enlazadas directamente desde picoteobaena.com (hotlinking) — funciona para prototipo, pero en producción real hay que migrarlas al hosting final
- Gelateo lleva un marcador visual honesto ("aún no tiene fotografía propia") en vez de foto de stock inventada
- Todo el motion respeta `prefers-reduced-motion`; foco de teclado visible en todos los elementos interactivos

---

## 12. Pendientes antes de producción

- [ ] Teléfono, horario y dirección exacta de **Guisoteo**
- [ ] Dirección exacta de **Traviola**
- [ ] Fotografía propia, sabores, horario exacto de **Gelateo** (reportaje completo pendiente)
- [ ] Testimonios reales con permiso explícito para la sección de opiniones (actualmente hay huecos/parafraseo de lo ya público)
- [ ] Confirmar con el cliente si Guisoteo o Gelateo incorporarán reparto a domicilio (afecta a `/para-llevar/`)
- [ ] Decidir ownership final de `/celebraciones-y-grupos/` (página centralizada del hub vs. colgada solo de Guisoteo)
- [ ] Investigación de keywords específica para Gelateo (heladería) — sin datos todavía
- [ ] Tercer competidor pendiente de analizar para el estudio de encabezados (solo se aportaron 2 de los 3 primeros resultados de Google)
- [ ] Migrar imágenes hotlinkeadas al hosting definitivo antes de publicar

---

## 13. Archivos entregados en este proyecto

1. `inventario-imagenes-picoteobaena.md` — todas las URLs de imágenes del sitio actual, por local
2. `arquitectura-seo-grupo-gastrobrio.md` — grupos de keywords, lógica anticanibalización, árbol de páginas
3. `copy-home-restaurante-en-baena.md` — copy completo de la página Home siguiendo la jerarquía H1-H3
4. `restaurante-en-baena.html` — prototipo funcional completo de la página Home