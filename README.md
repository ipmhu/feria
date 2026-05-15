# Sistema de Evaluación – Feria de Tecnología IPMHU 2025‑2026

<div align="center">

**Plataforma oficial para la evaluación de proyectos tecnológicos**  
*Instituto Politécnico Max Henríquez Ureña (IPMHU)*

</div>

<br>

**Ver en producción:** [Próximamente] – interno para jurados  
**Reportar incidencia:** mateodarlyng5@gmail.com

---

## Sobre el Proyecto

La **Feria de Tecnología IPMHU 2025‑2026** es un evento donde los cursos presentan proyectos innovadores. Este sistema digital reemplaza las hojas de evaluación en papel y permite a los jurados calificar cada exposición mediante una rúbrica estandarizada de **40 puntos** (4 criterios: Dominio del Tema, Innovación, Presentación e Impacto).

El sistema está diseñado para que cualquier jurado pueda acceder desde su propio dispositivo, validar la identidad del curso con un PIN único y emitir su calificación en tiempo real. Además, ofrece un panel de **Totales y Rankings** que actualiza automáticamente los promedios y detecta empates para que el jurado tome decisiones informadas.

---

## ¿Qué resuelve?

- Elimina el papeleo y el riesgo de perder evaluaciones.
- Permite a los jurados evaluar rápidamente desde cualquier lugar (celular, tablet o PC).
- Evita que un curso sea evaluado sin su consentimiento (sistema de PIN).
- Muestra al instante el promedio de cada curso y cuántos jurados han calificado.
- Detecta automáticamente empates en el primer lugar y alerta al jurado.
- Permite corregir una evaluación ya hecha (edición posterior con trazabilidad).

---

## Características principales

- **Inicio de sesión seguro** – Cada jurado tiene usuario y contraseña únicos.
- **Panel de Cursos** – Lista todos los cursos participantes, su proyecto y representantes.
- **Evaluación por PIN** – El jurado ingresa el PIN de 6 dígitos que el curso proporciona al momento de exponer.
- **Rúbrica interactiva** – Cuatro criterios, cuatro niveles de desempeño (Excelente:10, Bueno:7, Regular:5, Mejorar:2).
- **Resumen y confirmación** – Antes de guardar se muestra el puntaje total.
- **Ranking en vivo** – Promedios actualizados automáticamente, barras de progreso de cobertura (cuántos jurados han evaluado).
- **Edición de calificaciones** – Si un jurado cometió un error, puede modificar su evaluación desde el menú “Edición”. El sistema marca la corrección como “EDITADO”.
- **Desempate** – Detecta si hay más de un curso con el mismo promedio más alto y sugiere una resolución manual.
- **Diseño responsive** – Funciona perfectamente en móviles gracias al menú hamburguesa y vista adaptada.

---

## Tecnologías utilizadas

### Frontend

| Tecnología | Uso |
|------------|-----|
| HTML5      | Estructura de la interfaz |
| CSS3       | Estilos con variables CSS, grid, flexbox y transiciones |
| JavaScript (ES6+) | Lógica completa de evaluación, peticiones asíncronas y manejo del estado |
| Google Fonts | Tipografías: Share Tech Mono, Rajdhani, Exo 2 |

### Backend y base de datos

| Tecnología | Uso |
|------------|-----|
| Supabase (PostgreSQL) | Base de datos en la nube, tablas: `usuarios`, `cursos`, `representantes`, `evaluaciones` |
| REST API de Supabase | El frontend consume directamente los endpoints con la clave anónima (Row Level Security configurado) |

### Infraestructura

| Tecnología | Uso |
|------------|-----|
| GitHub Pages / servidor estático | Alojamiento de la interfaz (HTML/CSS/JS) |
| Supabase Cloud | Alojamiento de la base de datos y API |

---

## ¿Cómo usar el sistema?

1. **Acceso** – El coordinador entrega a cada jurado un usuario y contraseña.
2. **Panel principal** – Al ingresar se ven todos los cursos disponibles.
3. **Evaluar** – Ir al menú **Evaluar**, seleccionar un curso, pedir su PIN, responder los 4 criterios y confirmar.
4. **Ver ranking** – En **Totales** se observan los promedios actualizados en tiempo real y cuántos jurados faltan.
5. **Corregir** – Si se equivocó, usar **Edición** para modificar la calificación previamente guardada.
6. **Resolver empates** – En **Desempate** el sistema advierte si existe empate en el primer lugar.

---

## Créditos

Desarrollado para la **Feria de Tecnología IPMHU 2025‑2026** por:

**Robelin Mejías** & **Darlyng Mateo**  
*Apoyo técnico y coordinación del sistema de evaluación*

© 2025 – 2026 · Instituto Politécnico Max Henríquez Ureña
