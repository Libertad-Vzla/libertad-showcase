<div align="center">
  <img src="https://www.libertadvzla.com/Logo-Libertad-VZLA.png" alt="Libertad VZLA" width="160">
</div>

<p align="center">Periodismo ciudadano en Venezuela.</p>

<p align="center">
  <a href="https://www.libertadvzla.com">Sitio</a>
  &nbsp; <a href="https://www.libertadvzla.com/news">Noticias</a>
  &nbsp; <a href="https://www.libertadvzla.com/sos">SOS</a>
  &nbsp; <a href="https://www.libertadvzla.com/reportar">Reportar</a>
</p>

---

> Este repositorio es la explicación al detalle del proyecto, pensada para que cualquier persona o agente entienda qué es Libertad VZLA y qué hace. El código de la aplicación vive en un repositorio privado y el acceso es por invitación. Este repositorio no acepta pull requests de código.

## Qué es

Libertad VZLA es un medio de periodismo ciudadano para Venezuela. Recibe reportes de ciudadanos y publica notas de interés público con segmentación por estado y municipio.

Somos un equipo pequeño y en crecimiento. No prometemos revisar cada nota antes de publicarla: el equipo verifica lo que puede y se apoya en inteligencia artificial para procesar el volumen. Los reportes ciudadanos sí pasan por la revisión del equipo antes de convertirse en una nota. Cuando algo está en proceso, lo decimos, y pedimos paciencia. Somos transparentes sobre cómo trabajamos.

## Noticias

- Portada y sección de noticias ordenadas por relevancia y novedad.
- Filtros por categoría y por estado (los 24 estados y Distrito Capital). Cada nota lleva estado y municipio.
- Lectura con audio (voz del navegador), marcadores para guardar notas y bloque de artículos relacionados.
- Comentarios de la comunidad por niveles: los nuevos quedan en revisión y los miembros con trayectoria comentan al instante. La moderación combina una lista de palabras y una capa de IA que solo frena el daño real, nunca la opinión política.

## Cómo se producen las noticias

- Las notas se arman a partir de fuentes públicas configuradas por el equipo. Se descartan duplicados (por título y por similitud de contenido) y se reescriben con apoyo de IA, con clasificación automática de categoría y zona geográfica. Se publican de forma continua.
- Hay controles de calidad: largo mínimo, descarte de textos de relleno y una verificación final en la base de datos.
- Los reportes ciudadanos siguen un camino aparte: el equipo los revisa, los agrupa por hecho y, cuando corresponde, los convierte en una nota citando el origen.

## Reportar

- Cualquiera puede enviar un reporte de lo que pasa en su zona. La identidad de quien reporta se guarda separada del contenido y no se publica.
- Protección contra spam y validación en el servidor.
- Para emergencias hay un reporte con ubicación (GPS) y fotos, pensado para el SOS.

## SOS Venezuela

Herramienta de emergencia, activa desde el 24 de junio de 2026 por el terremoto. Reúne:

- **Personas desaparecidas:** buscar por nombre o cédula, reportar a alguien y reportar cuando una persona aparece. Al reportar una aparición, se le avisa al familiar que la había reportado.
- **Cruce con Localizados Venezuela:** al ver una ficha, la app la compara con personas ya ubicadas en hospitales o refugios (por cédula o nombre) y muestra posibles coincidencias para que la familia las verifique. Ayuda a no duplicar registros.
- **Alertas de sismo:** datos en tiempo real de USGS, con aviso al teléfono si la persona los activa (funciona como app, sin instalar).
- **Hospitales:** buscador con su estado (operativo, parcial o cerrado), líneas de emergencia y cómo llegar.
- **Guías de primeros auxilios:** material de Cruz Roja, OMS y FEMA, disponible sin conexión.
- **Mapas:** de reportes, personas y epicentros, y un mapa preliminar del daño en edificaciones de la zona afectada.
- **Orientación** legal, psicológica y médica, con un directorio de líneas de ayuda. Es orientación para encaminar a quien puede ayudar, no asesoría formal, con una línea de crisis siempre visible (911).
- **Mensajería privada** entre el familiar y quien tiene información, con envío de foto y ubicación. Las fotos se suben sin datos de ubicación.

## Panel ciudadano

- Perfil con modo anónimo activado por defecto; revelar la identidad es opcional.
- Trayectoria por etapas (de Ciudadano en adelante) que se gana demostrando competencias, no por puntaje.
- Aprendizaje: lecciones dentro de la app y cursos para aprender a verificar información y cuidar la seguridad digital; al completarlos se reconocen con insignias.
- Bandeja de avisos, tus comentarios y tus marcadores, todo privado.
- Sin rankings ni listas públicas de actividad.

## El equipo por dentro

- Un panel para el equipo: publicar y editar notas, revisar y agrupar reportes, moderar comentarios y aportes, revisar el aprendizaje y administrar las fuentes de noticias.
- Cada acción importante queda en un registro de auditoría: quién, qué y cuándo.

## Privacidad

La identidad de quien reporta se guarda separada del contenido y no se publica. Las fotos se suben sin datos de ubicación. No hay rankings ni listas públicas de actividad. Guardamos la menor cantidad posible de datos.

## Cómo está hecho

| Función | Descripción |
|:---|:---|
| Renderizado en servidor | El contenido se arma en el servidor antes de llegar al navegador. |
| Acceso por rol en la base de datos | Las reglas de acceso se aplican en la base de datos, no solo en la aplicación. |
| Autenticación en servidor | Las sesiones se gestionan del lado del servidor. |
| Distribución global | El contenido se sirve desde varios puntos geográficos. |
| Funciona como app | Se usa desde el navegador, sin instalar, y sirve con conexión débil. |
| Registro de auditoría | Las acciones importantes quedan registradas con fecha y responsable. |
| Minimización de datos | No se guarda información identificable que no se necesite. |

## Estado del proyecto

En producción en [libertadvzla.com](https://www.libertadvzla.com), con todo lo anterior funcionando. El equipo está en crecimiento.

## Cómo colaborar

El código vive en un repositorio privado y el acceso es por invitación. Las formas de aportar (voluntariado, periodismo, traducción, reportes de seguridad) están en la [guía de colaboración de la organización](https://github.com/Libertad-Vzla/.github/blob/main/CONTRIBUTING.md). Para cualquiera de esas vías, escribe a contacto@libertadvzla.com.

## Licencias

- **Código fuente:** Business Source License 1.1 (BSL 1.1).
- **Documentación:** Creative Commons Attribution 4.0 (CC BY 4.0).

## Contacto

- Sitio: [libertadvzla.com](https://www.libertadvzla.com)
- Correo: contacto@libertadvzla.com
- X: [@_Libertadvzla](https://x.com/_Libertadvzla)

---

## English

Libertad VZLA is a citizen-journalism outlet for Venezuela. Citizens report what happens in their area and we publish news with state and municipality segmentation. We are a small, growing team and we do not claim to verify every article before publishing: the team checks what it can and uses AI to process volume, while citizen reports do go through the team's review before becoming an article.

The platform includes regional news with leveled community comments and audio reading; SOS Venezuela, an emergency tool (active since the June 24, 2026 earthquake) for searching and reporting missing people, cross-checking with Localizados Venezuela, real-time USGS earthquake alerts, a hospital finder, offline first-aid guides, maps, and legal, psychological and medical orientation; citizen reporting with the reporter's identity kept separate; and a citizen panel for learning and participation, private by default. The site is public at libertadvzla.com; the source code is private and access is by invitation. Contact: contacto@libertadvzla.com.
