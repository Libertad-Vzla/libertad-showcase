<div align="center">
  <img src="https://www.libertadvzla.com/Logo-Libertad-VZLA.png" alt="Libertad VZLA" width="160">
</div>

<p align="center">Periodismo ciudadano en Venezuela.</p>

<p align="center">
  <a href="https://www.libertadvzla.com">Sitio</a>
  &nbsp; <a href="https://www.libertadvzla.com/news">Noticias</a>
  &nbsp; <a href="https://www.libertadvzla.com/victims">Memoria Viva</a>
  &nbsp; <a href="https://www.libertadvzla.com/sos">SOS</a>
  &nbsp; <a href="https://www.libertadvzla.com/reportar">Reportar</a>
</p>

---

> Este repositorio es la explicación al detalle del proyecto, pensada para que cualquier persona o agente entienda qué es Libertad VZLA y cómo funciona. El código de la aplicación vive en un repositorio privado y el acceso es por invitación. Este repositorio no acepta pull requests de código.

## Qué es

Libertad VZLA es un medio de periodismo ciudadano para Venezuela. Recibe reportes de ciudadanos y publica notas de interés público con segmentación por estado y municipio. La gente cuenta lo que pasa en su zona y nosotros lo ordenamos, lo procesamos y lo publicamos.

Somos un equipo pequeño y en crecimiento. No prometemos revisar cada reporte antes de publicarlo, porque no sería verdad: revisamos lo que podemos con el equipo y nos apoyamos en inteligencia artificial para procesar el volumen. Cuando algo está en proceso, lo decimos, y pedimos paciencia. Somos transparentes sobre cómo trabajamos; el foco es informar.

## Cómo funciona un reporte

1. **Ingreso.** El ciudadano envía un reporte. Su identidad se guarda separada del contenido para proteger a la fuente.
2. **Validación.** El reporte se valida en el servidor y se compara con lo ya publicado para detectar duplicados.
3. **Agrupación.** Los reportes de un mismo hecho se agrupan. La inteligencia artificial ayuda en tareas puntuales: detectar duplicados, preparar un borrador y clasificar la zona geográfica.
4. **Revisión y publicación.** El equipo revisa y contrasta contra fuentes lo que puede según la carga del momento, y publica. La identidad de quien reporta no se publica. Las acciones importantes quedan en un registro de auditoría.

La inteligencia artificial es una herramienta de trabajo. No genera noticias por su cuenta ni decide sola qué se publica.

## Secciones

- **Noticias.** Notas de interés público con segmentación regional por estado y municipio.
- **Memoria Viva.** Archivo público, actualizable y auditable de personas detenidas por motivos políticos en Venezuela: fichas con estatus legal, lugar de reclusión cuando se conoce y cronología documentada. El equipo acreditado actualiza los registros; cualquiera consulta lo publicado. Cada cambio queda registrado: quién, qué y cuándo.
- **SOS Venezuela.** Herramienta de emergencia, activa desde el 24 de junio de 2026 por el terremoto. Reúne reportes ciudadanos de emergencia, búsqueda de personas, un mapa de recursos y la ubicación de hospitales y centros de acopio, con un buscador. Pensada para ser útil en momentos de alta demanda, con una interfaz simple y de carga ligera.

## Cómo está hecho

| Función | Descripción |
|:---|:---|
| Renderizado en servidor | El contenido se arma en el servidor antes de llegar al navegador. |
| Acceso por rol en la base de datos | Las reglas de acceso se aplican en la base de datos, no solo en la aplicación. |
| Autenticación en servidor | Las sesiones se gestionan del lado del servidor. |
| Distribución global | El contenido se sirve desde varios puntos geográficos. |
| Registro de auditoría | Las acciones importantes quedan registradas con fecha y responsable. |
| Minimización de datos | No se guarda información identificable que no se necesite. |

## Privacidad

La identidad de quien reporta se guarda separada del contenido. El registro permite usar un seudónimo. No publicamos la identidad de las fuentes. La información de personas detenidas por motivos políticos es pública por diseño; los datos de menores se tratan según la ley.

## Estado del proyecto

La plataforma está en producción en [libertadvzla.com](https://www.libertadvzla.com): sitio público, registro con seudónimo, publicación de noticias con segmentación regional, SOS Venezuela y Memoria Viva. El equipo está en crecimiento.

## Cómo colaborar

El código vive en un repositorio privado y el acceso es por invitación. Las formas de aportar (voluntariado, periodismo, traducción, reportes de seguridad) están en la [guía de colaboración de la organización](https://github.com/Libertad-Vzla/.github/blob/main/CONTRIBUTING.md). Para cualquiera de esas vías, escribí a contacto@libertadvzla.com.

## Licencias

- **Código fuente:** Business Source License 1.1 (BSL 1.1). Uso comercial y productos derivados requieren licencia explícita.
- **Documentación:** Creative Commons Attribution 4.0 (CC BY 4.0).

## Contacto

- Sitio: [libertadvzla.com](https://www.libertadvzla.com)
- Correo: contacto@libertadvzla.com
- X: [@_Libertadvzla](https://x.com/_Libertadvzla)

---

## English

Libertad VZLA is a citizen-journalism outlet for Venezuela. Citizens submit reports; we keep the reporter's identity separate from the content, group reports about the same event, and the team reviews and cross-checks what it can before publishing, using AI to help process volume. We are a small, growing team and we do not claim to verify every report before publishing. The platform also runs Memoria Viva (a public, auditable record of people detained on political grounds) and SOS Venezuela (an emergency tool, active since the June 24, 2026 earthquake). The site is public at libertadvzla.com; the source code is private and access is by invitation. Contact: contacto@libertadvzla.com.
