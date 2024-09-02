Checkpoint 16

**1. ¿Por qué usamos Route Guards?**

**Qué es:**

- Un Route Guard es una función o clase en frameworks de desarrollo web, que se utiliza para controlar el acceso a rutas específicas dentro de una aplicación. Básicamente, actúa como una barrera que decide si un usuario puede o no acceder a una determinada ruta o página.

**Para qué sirve:**

- Su principal utilidad es proteger ciertas partes de la aplicación que no deberían ser accesibles para todos los usuarios. Por ejemplo, restringir el acceso a rutas de administración solo a usuarios que tengan permisos de administrador.
- Los Route Guards pueden verificar si el usuario está autenticado, tiene ciertos roles, ha aceptado términos y condiciones, o cualquier otra condición que defina el acceso a una ruta.

**Cuándo las utilizaremos:**

- Usaremos Route Guards cuando tengamos rutas en nuestra aplicación que necesiten algún tipo de protección o autorización. Esto es común en aplicaciones con varios niveles de acceso, como paneles de administración, cuentas de usuario, o secciones que manejan datos sensibles.

**Riesgos de usarlas:**

- **Complejidad:** Si se abusa de los Route Guards o se utilizan de manera inconsistente, la lógica de la navegación puede volverse compleja y difícil de mantener.
- **Performance:** Implementaciones ineficientes de Route Guards podrían impactar la velocidad de carga de la aplicación, especialmente si realizan comprobaciones costosas.

**Riesgos de no usarlas:**

- **Seguridad:** Sin Route Guards, cualquier usuario podría intentar acceder a rutas sensibles simplemente conociendo la URL, lo que podría comprometer la seguridad de la aplicación.
- **Mala experiencia de usuario:** Podría resultar en situaciones donde un usuario acceda a contenido que no debería ver, generando confusión o errores inesperados.
-----
**2. ¿Qué es una solicitud POST?**

**Qué es:**

- Una solicitud POST es uno de los métodos HTTP utilizados por los navegadores web para enviar datos al servidor. En una solicitud POST, los datos se incluyen en el cuerpo de la solicitud, en lugar de en la URL, como sucede con GET.

**Para qué sirve:**

- Se utiliza principalmente para enviar datos que necesitan ser procesados por el servidor, como formularios, datos de autenticación, archivos, etc.
- A diferencia de una solicitud GET, que se usa para recuperar datos, POST se utiliza para crear o modificar recursos en el servidor.

**Cuándo las utilizaremos:**

- Usaremos solicitudes POST cuando necesitemos enviar datos que no deberían ser visibles en la URL o cuando estamos enviando información que será utilizada para modificar o crear recursos en el servidor.
- Ejemplos comunes incluyen:
  - Enviar un formulario de registro de usuario.
  - Subir un archivo.
  - Hacer una compra en línea.

**Riesgos de usarlas:**

- **Seguridad:** Aunque los datos no son visibles en la URL, no están cifrados por defecto. Es crucial usar HTTPS para asegurar que los datos transmitidos no puedan ser interceptados por terceros.
- **Carga en el servidor:** Las solicitudes POST pueden generar una carga adicional en el servidor, especialmente si se están subiendo archivos grandes o enviando datos extensos.

**Riesgos de no usarlas:**

- **Falta de funcionalidad:** Si no utilizamos POST cuando es necesario, podríamos estar forzando el uso de GET para acciones que no son apropiadas, lo cual puede llevar a problemas de seguridad y mal funcionamiento.
- **Límites de URL:** GET tiene limitaciones en la cantidad de datos que se pueden enviar a través de la URL, lo que podría truncar o perder datos importantes si intentamos usar GET en lugar de POST.
-----
**3. ¿Cuáles son algunas cosas que puede hacer para prepararse para las entrevistas de trabajo?**

**Preparación Técnica:**

- **Repaso de conceptos fundamentales:**
  - Asegurarse de repasar conceptos clave de programación y estructuras de datos como listas, árboles, grafos, pilas, colas, y algoritmos comunes como búsqueda, ordenamiento, recursión, etc.
  - Práctica con problemas de codificación en plataformas como LeetCode, HackerRank, o Codewars. Estas plataformas te permiten trabajar en problemas que suelen ser similares a los que te encontrarás en entrevistas.
- **Revisión de proyectos pasados:**
  - Revisar tus proyectos anteriores, especialmente aquellos que están en tu portafolio o CV. Asegúrate de poder explicar claramente tu rol, los desafíos que enfrentaste y cómo los resolviste.
  - Prepárate para hablar sobre el código que escribiste, las decisiones arquitectónicas que tomaste, y las tecnologías que utilizaste.

**Investigación de la Empresa:**

- **Estudio de la empresa:**
  - Visita la página web de la empresa, especialmente secciones como "Sobre nosotros", "Carreras", y cualquier sección que hable de sus valores, misión, y cultura.
  - Investiga sus productos o servicios principales. ¿Qué problemas resuelven? ¿Cómo encaja tu experiencia en sus necesidades?
  - Lee noticias recientes sobre la empresa en Google News o redes sociales para estar al tanto de sus últimas iniciativas, cambios, o logros.
- **Conocer la cultura:**
  - Revisa plataformas como Glassdoor para leer reseñas de empleados actuales y anteriores. Esto te dará una idea de la cultura laboral y te preparará para preguntas sobre cómo encajarías en su equipo.

**Preparación para Preguntas Comunes:**

- **Preguntas técnicas:**
  - Prepara respuestas para preguntas técnicas comunes en tu campo. Esto podría incluir cómo funcionan ciertos algoritmos, explicaciones sobre bases de datos, redes, patrones de diseño, etc.
- **Preguntas conductuales:**
  - Practica respuestas a preguntas conductuales usando el método STAR (Situación, Tarea, Acción, Resultado). Esto te ayudará a estructurar tus respuestas de manera clara y concisa.
  - Preguntas comunes incluyen: "Háblame de un momento en que enfrentaste un desafío", "¿Cómo manejas el trabajo en equipo?", o "Descríbeme un proyecto del que estés particularmente orgulloso".

**Preparación Emocional y Mental:**

- **Manejo del estrés:**
  - Realiza ejercicios de respiración profunda y meditación para reducir el estrés antes de la entrevista.
  - Practica entrevistas simuladas con un amigo o mentor para ganar confianza y reducir la ansiedad.
- **Establece una rutina:**
  - Duerme bien la noche anterior y realiza una rutina matutina que te relaje, como hacer ejercicio ligero, leer algo inspirador, o escuchar música.
  - Evita la cafeína en exceso, ya que puede aumentar la ansiedad.
- **Visualiza el éxito:**
  - Tómate unos minutos para visualizar una entrevista exitosa. Imagina cómo responderás a las preguntas con confianza y cómo te sentirás al final de la entrevista habiendo hecho tu mejor esfuerzo.

**Preparación Logística:**

- **Prueba tu tecnología:**
  - Si la entrevista es en línea, asegúrate de que tu cámara, micrófono, y conexión a internet funcionen correctamente.
  - Ten una copia de tu CV y cualquier otro material relevante a mano, ya sea en papel o en formato digital.
- **Vestimenta:**
  - Viste de manera profesional, aunque la entrevista sea virtual. Esto no solo te hará ver bien, sino que también te ayudará a sentirte más seguro.
- **Puntualidad:**
  - Llega o conéctate unos minutos antes de la hora acordada para demostrar tu puntualidad y preparación.

**Después de la Entrevista:**

- **Seguimiento:**
  - Envía un correo de agradecimiento dentro de las 24 horas posteriores a la entrevista. Agradece al entrevistador por su tiempo y reitera tu interés en el puesto.
  - Si hubo alguna pregunta que no pudiste responder completamente, usa esta oportunidad para dar una respuesta más detallada.
- **Reflexiona sobre la entrevista:**
  - Tómate un tiempo para reflexionar sobre qué fue bien y qué podrías mejorar para futuras entrevistas.

