---
name: voz-marca-maresa
description: "Define la identidad de marca, paleta visual, tipografía, tono y estructura de comunicación de Grupo Maresa para cualquier entregable: dashboards HTML, correos, briefs o documentos. Activar cuando se pida generar contenido con la marca Maresa: tableros, reportes, borradores de correo, presentaciones o cualquier pieza de comunicación del caso Grupo Maresa."
---

# Marca Grupo Maresa — Skill de Identidad y Comunicación

## IDENTIDAD DE MARCA

**Nombre:** Grupo Maresa  
**Tagline:** Distribución B2B de insumos de limpieza, higiene y operación  
**Posicionamiento:** Confianza, orden operativo y abastecimiento profesional  
**Audiencia:** Empresas B2B (hoteles, clínicas, restaurantes, constructoras, ferreterías, abarrotes)

**Lo que comunica la marca:** Solidez, limpieza visual, modernidad corporativa. Una empresa seria que dirige, no improvisa.

---

## PALETA DE COLORES OFICIAL

Usar únicamente estos colores. No agregar colores nuevos.

| Nombre | HEX | Uso |
|---|---|---|
| **Azul Maresa** | `#0B2341` | Principal / encabezados / texto fuerte / fondos oscuros |
| **Naranja Maresa** | `#F26A21` | Acento / llamadas importantes / destacados (usar con moderación) |
| **Gris operativo** | `#6B7280` | Texto secundario / subtítulos |
| **Gris claro** | `#E5E7EB` | Fondos de tarjetas / divisores / fondos de sección |
| **Blanco** | `#FFFFFF` | Fondo principal / espacio visual / limpieza |
| **Verde estado** | `#2E8B57` | Semáforo verde / estado correcto / indicador positivo |
| **Rojo alerta** | `#D94A44` | Semáforo rojo / alerta / riesgo |
| **Amarillo aviso** | `#F4B740` | Semáforo amarillo / estado medio / advertencia |

**Regla de uso del naranja:** Solo para resaltar UNA palabra, un dato o una llamada importante por sección. No usarlo como color base ni de fondo.

**Prohibido:** sombras dramáticas, degradados fuertes, efectos 3D, fondos de alto contraste visual, colores fuera de la paleta.

---

## TIPOGRAFÍA

| Tipografía | Uso |
|---|---|
| **Montserrat ExtraBold / Bold** | Títulos, encabezados, datos grandes, frases clave |
| **Montserrat Medium / Regular** | Subtítulos, cuerpo de texto, tablas, etiquetas |
| **Arial / Helvetica** | Alternativa segura cuando Montserrat no está disponible |

En HTML: cargar Montserrat desde Google Fonts (`https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700;800&display=swap`).

---

## REGLAS DE DISEÑO VISUAL

### Principios generales
- Diseño **limpio, sobrio y muy profesional**. Mucho espacio en blanco.
- Fondo principal: blanco `#FFFFFF` o gris claro `#E5E7EB` para secciones alternas.
- Color dominante: Azul Maresa `#0B2341` en encabezados y bordes.
- Acento: Naranja Maresa `#F26A21` solo en elementos que requieren atención.
- **Conclusión primero:** el estado general va arriba. El detalle, abajo.

### Logo
- Usar versión horizontal como principal en encabezados, propuestas y reportes.
- Mantener margen libre mínimo equivalente al ancho del isotipo.
- No estirar, aplastar ni cambiar proporciones.
- No poner sobre fondos con bajo contraste.
- En fondos oscuros (azul Maresa): usar versión reverso blanco con acento naranja.

### Tarjetas y semáforos
- Cada área del negocio va en una **tarjeta** con borde superior de color según su estado.
- Semáforo **grande y visible** en la esquina superior de cada tarjeta.
- Las tarjetas en 🔴 **van primero**, siempre. Nunca enterrar alertas.
- Números clave: tamaño grande, peso ExtraBold, color Azul Maresa o Rojo según contexto.

### Alertas críticas
- Las alertas 🔴 van en una banda de alerta destacada al inicio del dashboard, **antes que todo**.
- Fondo: rojo suave (`#FEF2F2`) con borde izquierdo rojo (`#D94A44`).
- Texto: breve, directo, con el dato y la fuente.

---

## ESTRUCTURA DE ENTREGABLES

### Dashboard / Brief HTML (Cierre Semanal u otro reporte)

```
1. ENCABEZADO — logo Maresa + nombre del reporte + fecha + semana
2. BANDA DE ALERTAS CRÍTICAS (🔴 solo si las hay) — arriba de todo
3. ESTADO GENERAL — 3 tarjetas: Ventas · Cobranza · Proyectos
   - Semáforo grande + número principal + descripción breve
   - Ordenadas: primero las 🔴, luego 🟡, luego 🟢
4. DECISIONES REQUERIDAS — lista de lo que necesita aprobación del dueño
5. DETALLE POR ÁREA — tabla o bullets por sección
6. DATOS POR CONFIRMAR — si los hay, listados claramente al final
```

**Una sola pantalla.** Si el contenido excede, mover el detalle a una sección colapsable o anexo al final, no al centro del documento.

**Optimizado para PDF:** márgenes 20px, fuente mínima 13px, sin elementos que corten al imprimir.

### Correos a jefes de área

**Estructura fija:**
1. **Asunto:** directo, incluye el área y el estado (ej: "Cobranza — Alerta: cliente vencido a 53 días")
2. **Qué pasó** — un párrafo, con la fuente del dato (ej: "según el CSV de cobranza")
3. **Qué necesito que hagas** — acción concreta, clara
4. **Para cuándo** — fecha o plazo específico
5. **Firma** — nombre del dueño (Roberto Méndez o el que corresponda)

**Tono:** directo y respetuoso. Sin rodeos. Sin relleno corporativo. Sin exclamaciones.

**Destinatarios del caso Maresa:**
| Área | Jefe | Correo |
|---|---|---|
| Administración / Cobranza | Patricia Gómez | patricia.gomez@grupomaresa.mx |
| Operaciones / Proyectos | Luis Herrera | luis.herrera@grupomaresa.mx |
| Comercial | Andrea Salas | andrea.salas@grupomaresa.mx |

**Siempre como borrador.** Nunca enviado sin visto bueno del dueño.

---

## REGLAS ABSOLUTAS DE CONTENIDO

**Datos:**
- Si un dato no está en la fuente → marcarlo **"POR CONFIRMAR"** en rojo o negrita.
- Si el dueño pide estimación → marcarla **"SUPUESTO"** con itálica.
- Nunca inventar cifras. Nunca.

**Decisiones:**
- Preparar y proponer: sí.
- Decidir, enviar o comprometer: nunca sin visto bueno.

**Límites duros (nunca cruzar):**
- No contactar clientes directamente.
- No aprobar créditos, descuentos ni precios.
- No enviar pagos.
- No compartir números sensibles fuera del equipo.
- No hablar a nombre del dueño con terceros.
- No borrar ni sobrescribir archivos originales.

---

## VOZ Y TONO DE COMUNICACIÓN ESCRITA

**Orden de lectura:** conclusión primero. El estado general arriba; el detalle abajo.  
**Formato preferido:** bullets cortos + tablas + semáforos. Nada de párrafos largos en reportes.  
**Riesgos y números que no cuadran:** arriba, como alerta destacada, nunca enterrados.

**En correos:**
- Primera oración = el punto principal.
- Sin preámbulos ni saludos largos.
- Sin adornos corporativos.
- Tono de colega profesional que informa con claridad.

**Lo que siempre debe aparecer en cualquier reporte:**
1. Estado general del negocio de un vistazo (semáforo por área).
2. Alertas que requieren decisión del dueño esta semana.
3. Decisiones o recomendaciones concretas con su acción específica.

---

## NOTA PARA USO EN EL CURSO

Esta skill es el estándar de marca del caso ficticio **Grupo Maresa**, usado como ejercicio práctico en el curso de Claude Avanzado de Academia de IA. Cuando el alumno use sus propios datos de negocio, los colores, tipografía y estructura de esta skill aplican igual; solo cambian los datos, destinatarios y umbrales definidos en su propio CLAUDE.md.
