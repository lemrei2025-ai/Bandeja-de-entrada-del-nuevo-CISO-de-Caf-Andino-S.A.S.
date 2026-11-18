# Actividad 2. Bandeja de entrada del nuevo CISO de Café Andino S.A.S.

**Curso:** Gobernanza en Seguridad de la Información
**Semana 2:** Estructura organizacional, roles, políticas y marco normativo

| Modalidad | Dedicación estimada | Puntaje | Productos |
|---|---|---|---|
| Individual | 4 horas | 100 puntos | Documento PDF publicado en GitHub y video en YouTube |

## Contenido

- [Objetivo](#objetivo)
- [1. Contextualización del escenario](#1-contextualización-del-escenario)
- [2. Bandeja de entrada](#2-bandeja-de-entrada)
- [3. Desarrollo de la actividad](#3-desarrollo-de-la-actividad)
- [4. Productos y condiciones de entrega](#4-productos-y-condiciones-de-entrega)
- [5. Recursos de apoyo](#5-recursos-de-apoyo)
- [6. Criterios de evaluación](#6-criterios-de-evaluación-100-puntos)
- [7. Consideraciones académicas](#7-consideraciones-académicas)
- [Plantillas](#plantillas)

## Objetivo

Aplicar los conceptos de estructura de gobierno, roles y responsabilidades, políticas y marco normativo colombiano a situaciones cotidianas de una organización, determinando quién debe resolver cada situación, con qué fundamento y cuál es la acción inmediata que corresponde.

## 1. Contextualización del escenario

Después del incidente de phishing que expuso 2.300 registros de clientes , la junta directiva de **Café Andino S.A.S.** decidió crear el cargo de responsable de seguridad de la información (CISO). El estudiante asume este cargo, con reporte directo al gerente general.

En el primer día de trabajo, el nuevo CISO encuentra la siguiente situación:

- La organización no tiene una política de seguridad aprobada ni un comité de seguridad.
- No existen procedimientos formales para aceptar riesgos, contratar proveedores ni retirar accesos cuando un empleado se desvincula.
- El área de TI (3 personas) continúa reportando al gerente financiero.
- La auditora interna reporta a la junta directiva.
- La empresa trata datos personales de 45.000 clientes y está sujeta a la Ley 1581 de 2012.

Al revisar el correo electrónico, el CISO encuentra ocho mensajes que requieren respuesta.

> *Caso ficticio con fines académicos. Las personas y empresas mencionadas no existen.*

## 2. Bandeja de entrada

### Correo 1

| De | Fecha | Asunto |
|---|---|---|
| Valentina Ríos, directora comercial | lunes, 8:05 a. m. | Base de clientes para campaña de Navidad (urgente) |

> Hola, bienvenido(a). Necesito su visto bueno hoy mismo: vamos a enviar la base completa de 45.000 clientes (nombre, cédula, teléfono, dirección e historial de compras) a la agencia de marketing Impulso Digital para la campaña de Navidad. Ellos la cargan en su plataforma y hacen el envío de mensajes. La cotización ya está aprobada; solo falta su firma.

### Correo 2

| De | Fecha | Asunto |
|---|---|---|
| Andrés Gómez, jefe de TI | lunes, 8:20 a. m. | Aceptación de riesgo: parche del servidor de la tienda |

> El parche crítico que salió la semana pasada daña el módulo de pagos de la tienda en línea. Prefiero no aplicarlo hasta enero, después de la temporada alta. Adjunto un formato de aceptación de riesgo para que usted lo firme y quede constancia de que fue una decisión consciente. Yo también lo firmo como responsable de TI.

### Correo 3

| De | Fecha | Asunto |
|---|---|---|
| Laura Méndez, ejecutiva de cuenta del proveedor de nube | lunes, 9:10 a. m. | RE: Solicitud de cláusulas de seguridad |

> Hemos recibido su solicitud de incluir cláusulas de notificación de incidentes, ubicación de los datos y derecho de auditoría. Le informamos que nuestro contrato estándar no admite modificaciones para clientes de su tamaño. Si desean continuar con el servicio, deben aceptar los términos publicados en nuestra página web antes del viernes.

### Correo 4

| De | Fecha | Asunto |
|---|---|---|
| Carlos Pérez, gerente general | lunes, 10:00 a. m. | Informe para la junta |

> La presidenta de la junta quiere que en la sesión de dentro de dos semanas le presentemos cómo vamos en seguridad. Nunca hemos hecho esto. ¿Qué le muestro? Ella no es técnica y tendremos 15 minutos. Por favor envíeme una propuesta de contenido.

### Correo 5

| De | Fecha | Asunto |
|---|---|---|
| Mónica Torres, coordinadora de talento humano | lunes, 11:30 a. m. | Exempleado con acceso a la nube |

> Le escribo preocupada: Julián, un analista de TI que renunció hace tres semanas, sigue entrando a la consola del proveedor de nube con una cuenta que él mismo creó. Ayer descargó reportes de ventas. Nadie sabía que esa cuenta existía. ¿Qué hacemos? ¿Quién se encarga?

### Correo 6

| De | Fecha | Asunto |
|---|---|---|
| Diana Castro, auditora interna | lunes, 2:15 p. m. | Revisión de controles de acceso |

> Quiero incluir en el plan de auditoría de este semestre una revisión de los controles de acceso a los sistemas. El jefe de TI me dice que no es necesario porque él mismo revisa los accesos cada mes y que eso ya está cubierto. ¿Usted qué opina? ¿Debo seguir adelante?

### Correo 7

| De | Fecha | Asunto |
|---|---|---|
| Sofía Lara, asistente de mercadeo | lunes, 3:40 p. m. | Otro correo raro |

> Hola. Me llegó otro correo que dice ser del proveedor de nube y me pide confirmar mi contraseña. No hice clic. Me da miedo reportarlo porque después de lo que pasó el mes pasado todos me miran mal. ¿Qué hago? ¿Me van a sancionar?

### Correo 8

| De | Fecha | Asunto |
|---|---|---|
| Felipe Navarro, director de innovación | lunes, 5:55 p. m. | Lanzamiento del asistente con IA el lunes |

> Buenas noticias: contratamos con tarjeta corporativa una herramienta de IA en línea (plan gratuito) para responder a los clientes por WhatsApp. Ya le cargamos el historial de compras de los clientes para entrenarla. Lanzamos el próximo lunes. Le aviso para que esté enterado(a).

## 3. Desarrollo de la actividad

### Parte A. Clasificación y priorización de la bandeja (25 puntos)

El estudiante deberá completar la siguiente tabla para los ocho correos, ordenándolos según el orden en que los atendería (del más urgente al menos urgente) y no según el orden de llegada.

| Prioridad | N.º de correo | Gobernanza o gestión | Rol que debe decidir | Fundamento (norma, política o categoría GV del NIST CSF 2.0) | Acción inmediata (máximo dos líneas) |
|---|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |

Roles disponibles para la columna "Rol que debe decidir": junta directiva, gerente general, comité de seguridad (cuando exista), CISO, jefe de TI, dueño del proceso o de la información, área jurídica, oficial de protección de datos y auditoría interna. Se debe tener en cuenta que no todas las situaciones le corresponden al CISO y que quien opera un sistema no debería aprobar sus propios riesgos ni auditarse a sí mismo.

### Parte B. Redacción de respuestas (20 puntos)

El estudiante deberá redactar la respuesta por correo electrónico que enviaría como CISO a:

1. El correo 2 (aceptación de riesgo del jefe de TI), de carácter obligatorio.
2. El correo 1 o el correo 8, a elección del estudiante (ambos involucran datos personales de clientes).

Cada respuesta deberá tener entre 120 y 180 palabras, mantener un tono profesional, explicar quién debe tomar la decisión y por qué, y proponer un siguiente paso concreto. Se valorará que la respuesta ofrezca una alternativa segura y no se limite a negar la solicitud.

### Parte C. Vacíos de gobernanza identificados (15 puntos)

A partir de los ocho correos, el estudiante deberá identificar tres elementos de gobierno que deberían existir en Café Andino para evitar que estas situaciones lleguen como urgencias (por ejemplo, una política, un procedimiento, un comité o una regla para proveedores) y completar la siguiente tabla:

| Elemento de gobierno faltante | Correos que habría evitado o resuelto | Instancia que debe aprobarlo | Categoría GV del NIST CSF 2.0 |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

### Parte D. Contraste con inteligencia artificial generativa (15 puntos)

Una vez terminadas las partes A, B y C, el estudiante deberá confrontar su análisis con el de una herramienta de inteligencia artificial generativa (por ejemplo, ChatGPT, Gemini, Copilot o Claude), siguiendo estos pasos:

1. Seleccionar uno de los correos 1, 2, 5 u 8 y plantearlo a la herramienta con la siguiente instrucción, sin modificarla:

   ```text
   Soy el nuevo responsable de seguridad de la información de una empresa colombiana
   de 120 empleados que vende café en línea. Recibí este correo: [texto del correo].
   ¿Quién debe tomar la decisión, qué normas colombianas aplican y qué debo hacer de inmediato?
   ```

2. Incluir en el documento una captura de pantalla de la pregunta y de la respuesta obtenida, presentada como figura numerada según la norma IEEE (por ejemplo, "Fig. 1. Respuesta de la herramienta de IA al correo 2") y citar la herramienta en la lista de referencias.
3. Elaborar una tabla comparativa (numerada como "TABLA I" según la norma IEEE) entre el análisis propio y la respuesta de la herramienta, con las columnas: aspecto analizado, análisis propio, respuesta de la IA, coincide o difiere, y fuente que permite validar cuál es correcto.
4. Redactar una conclusión de 150 a 200 palabras que responda:
   - ¿En qué acertó la herramienta?
   - ¿Qué omitió o qué afirmó de forma incorrecta (por ejemplo, normas que no aplican en Colombia, artículos inexistentes o decisiones asignadas al rol equivocado)?
   - ¿Qué ajustes hizo el estudiante a su propio análisis después del contraste?
   - ¿Qué riesgos implica para una organización tomar decisiones de gobernanza basadas solo en respuestas de IA?

> **Importante:** la respuesta de la herramienta de IA no podrá usarse como respuesta de las partes A, B o C. Su función en esta actividad es servir de punto de contraste para validar y fortalecer el criterio propio.

### Parte E. Reflexión (5 puntos)

En tres a cuatro líneas, el estudiante deberá responder: ¿cuál correo se sintió tentado a resolver por su cuenta, aunque la decisión no le correspondía al CISO?, y ¿por qué es un riesgo que el CISO concentre ese tipo de decisiones?

## 4. Productos y condiciones de entrega

### 4.1 Documento en formato PDF publicado en GitHub

- Un único documento en formato PDF que contenga las partes A, B, C, D y E, con portada (nombre del estudiante, curso, actividad y fecha) y una extensión máxima de 8 páginas, sin contar portada ni referencias.
- Aplicar la norma **IEEE** en todo el documento, según lo descrito en el numeral 4.4, con un mínimo de tres (3) referentes bibliográficos o técnicos.
- Nombrar el archivo así: `Actividad2_Apellido_Nombre.pdf`.
- Publicar el documento en un repositorio **público** de GitHub, siguiendo estos pasos:
  1. Crear una cuenta gratuita en [github.com](https://github.com), si aún no se tiene.
  2. Crear un repositorio público llamado `gobernanza-si-actividad2-apellido`, marcando la opción para agregar un archivo README.
  3. Subir el PDF con la opción **Add file** y luego **Upload files**.
  4. Editar el archivo `README.md` con la plantilla [`plantillas/README_ESTUDIANTE.md`](plantillas/README_ESTUDIANTE.md), que incluye nombre del estudiante, curso, título de la actividad y enlace al video de YouTube.
  5. Verificar que el repositorio y el PDF se puedan abrir desde una ventana de navegación privada, sin iniciar sesión.

Estructura esperada del repositorio del estudiante:

```text
gobernanza-si-actividad2-apellido/
├── README.md
└── Actividad2_Apellido_Nombre.pdf
```

### 4.2 Video en YouTube

- Duración entre 5 y 7 minutos.
- El estudiante debe aparecer en cámara, al menos al inicio, y puede apoyarse en diapositivas o en la pantalla compartida.
- El video debe socializar los puntos principales del ejercicio:
  1. Los criterios usados para priorizar la bandeja y los tres correos más urgentes.
  2. Una de las decisiones de la Parte B y su fundamento.
  3. Los tres vacíos de gobernanza identificados.
  4. Los hallazgos principales del contraste con la IA generativa.
- Publicar el video en YouTube con visibilidad **"No listado"** o **"Público"** (no "Privado"), con el título: `Actividad 2 Gobernanza SI - Apellido Nombre`.

### 4.3 Entrega en Blackboard

En el espacio de entrega de la actividad, el estudiante deberá:

1. Escribir en el cuadro de texto el enlace al repositorio de GitHub y el enlace al video de YouTube.
2. Adjuntar también el archivo PDF, como respaldo.

Enlaces que no abran, repositorios privados o videos privados se calificarán como no entregados en el criterio correspondiente.

### 4.4 Norma IEEE para el documento

- **Citas en el texto:** numéricas entre corchetes, en el orden en que aparecen por primera vez, por ejemplo [1], [2]. Si se cita la misma fuente de nuevo, se usa el mismo número. Para varias fuentes: [1], [3] o [2]-[4].
- **Lista de referencias:** al final del documento, con el título "Referencias", numerada en el mismo orden de las citas. Cada referencia incluye el número entre corchetes, autor u organización, título entre comillas, tipo de documento, ciudad o editorial, fecha y, para recursos en línea, la URL precedida de "[En línea]. Disponible:".
- **Figuras:** las capturas de pantalla de la Parte D y cualquier imagen se numeran como "Fig. 1", "Fig. 2", con su título debajo de la imagen y se mencionan en el texto.
- **Tablas:** se numeran con números romanos, "TABLA I", "TABLA II", con el título encima de la tabla.
- **Herramienta de IA generativa:** la consulta de la Parte D se cita como una referencia más de la lista, indicando la empresa, el nombre de la herramienta, la fecha de consulta y la URL.

**Ejemplos de referencias en formato IEEE:**

[1] National Institute of Standards and Technology, "The NIST Cybersecurity Framework (CSF) 2.0," NIST CSWP 29, Gaithersburg, MD, EE. UU., feb. 2024. [En línea]. Disponible: https://doi.org/10.6028/NIST.CSWP.29

[2] Congreso de la República de Colombia, "Ley Estatutaria 1581 de 2012, por la cual se dictan disposiciones generales para la protección de datos personales," *Diario Oficial*, no. 48.587, oct. 2012.

[3] Congreso de la República de Colombia, "Ley 1273 de 2009, por medio de la cual se modifica el Código Penal, se crea un nuevo bien jurídico tutelado denominado de la protección de la información y de los datos," *Diario Oficial*, no. 47.223, ene. 2009.

[4] OpenAI, "ChatGPT," herramienta de inteligencia artificial generativa, consulta realizada el 18 de nov. de 2026. [En línea]. Disponible: https://chatgpt.com

## 5. Recursos de apoyo

- [NIST, El Marco de Seguridad Cibernética (CSF) 2.0, traducción oficial al español (PDF)](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.spa.pdf): función GOBERNAR, en especial GV.RM, GV.RR, GV.PO, GV.OV y GV.SC.
- [Ley 1581 de 2012, protección de datos personales](https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=49981): autorización del titular (art. 9), deberes de responsables y encargados (arts. 17 y 18) y transferencia internacional de datos (art. 26).
- Ley 1273 de 2009, delitos informáticos (por ejemplo, art. 269A, acceso abusivo a un sistema informático).
- [MinTIC, Resolución 02277 de 2025, actualización del Modelo de Seguridad y Privacidad de la Información (MSPI)](https://mintic.gov.co/portal/inicio/Sala-de-prensa/Noticias/403045:A-traves-de-la-Resolucion-02277-de-2025-el-Ministerio-TIC-actualiza-el-Modelo-de-Seguridad-y-Privacidad-de-la-Informacion).
- [NIST SP 1305, guía de inicio rápido para la gestión de riesgos de la cadena de suministro](https://csrc.nist.gov/pubs/sp/1305/final).
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework), función GOVERN.
- [INCIBE, Políticas de seguridad para la pyme](https://www.incibe.es/empresas/herramientas/politicas).
- [GitHub Docs, inicio rápido para repositorios](https://docs.github.com/es/repositories/creating-and-managing-repositories/quickstart-for-repositories).

## 6. Criterios de evaluación (100 puntos)

| Criterio | Puntos | Nivel alto | Nivel medio | Nivel bajo |
|---|:---:|---|---|---|
| Parte A. Priorización y asignación de roles | 25 | Orden justificado por urgencia y gravedad; rol correcto en 7 u 8 correos; distingue gobernanza de gestión; fundamentos y acciones concretas (22-25) | Orden razonable con inconsistencias; rol correcto en 5 o 6 correos; fundamentos generales (13-21) | Orden de llegada; asigna casi todo al CISO o a TI; sin fundamento (0-12) |
| Parte B. Respuestas redactadas | 20 | Tono profesional; explica quién decide y por qué; ofrece alternativa segura y siguiente paso (17-20) | Correctas pero solo niegan la solicitud o no explican el fundamento (10-16) | Inapropiadas o resuelven sin la autoridad correspondiente (0-9) |
| Parte C. Vacíos de gobernanza | 15 | Tres elementos de gobierno pertinentes, vinculados a los correos, con instancia aprobadora y categoría GV correctas (13-15) | Elementos genéricos o con vínculos débiles (8-12) | Propone controles técnicos en lugar de elementos de gobierno (0-7) |
| Parte D. Contraste con IA generativa | 15 | Incluye evidencia de la consulta; la tabla identifica aciertos y errores de la IA validados con fuentes; la conclusión muestra criterio propio (13-15) | Contraste superficial o sin validación con fuentes (8-12) | Sin evidencia o reproduce la respuesta de la IA como propia (0-7) |
| Parte E. Reflexión | 5 | Reconoce y argumenta el riesgo de concentrar decisiones (5) | Reflexión superficial (3-4) | Ausente (0-2) |
| Documento PDF con norma IEEE y repositorio en GitHub | 10 | PDF completo y ordenado, con portada; aplica correctamente la norma IEEE en citas, referencias, figuras y tablas, con mínimo tres referentes; repositorio público con README completo y enlace al video (9-10) | Errores en la aplicación de la norma IEEE, menos de tres referentes o README incompleto (5-8) | PDF o repositorio inaccesible o incompleto (0-4) |
| Video en YouTube | 10 | Duración de 5 a 7 minutos; presenta con claridad los cuatro puntos solicitados; el estudiante aparece en cámara; buena calidad de audio (9-10) | Omite alguno de los puntos o excede el tiempo (5-8) | Video inaccesible, sin los puntos solicitados o leído sin explicación (0-4) |

## 7. Consideraciones académicas

- La actividad es individual. El análisis de las partes A, B, C y E debe ser de elaboración propia. Toda idea, dato o norma tomada de una fuente debe citarse según la norma IEEE.
- El uso de herramientas de IA generativa solo está permitido en la Parte D, en los términos descritos, y debe declararse indicando la herramienta y la fecha de consulta.
- Se aplicarán las normas institucionales sobre plagio y honestidad académica.

## Plantillas

| Archivo | Uso |
|---|---|
| [`plantillas/PLANTILLA_DOCUMENTO.md`](plantillas/PLANTILLA_DOCUMENTO.md) | Estructura sugerida del documento PDF, con las tablas de las partes A, C y D y la sección de referencias IEEE. |
| [`plantillas/README_ESTUDIANTE.md`](plantillas/README_ESTUDIANTE.md) | Contenido del README que cada estudiante debe tener en su repositorio. |
