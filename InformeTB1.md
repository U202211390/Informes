# Universidad Peruana de Ciencias Aplicadas
### INFORME DEL TRABAJO 1 (TB1)
![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/c8a24a74-515a-436b-b7b9-ea1b2e418e60)

**Curso:** Desarrollo de Aplicaciones Open Source

**Sección:** SW54

**Profesor:** Efrain Bautista

**Carrera:** Ingeniería de Software

**Ciclo:** 2024-01

**Startup:** CodePace

**Producto:** GetWork

### Integrantes:

| Nombre                            | Código       |
|-----------------------------------|--------------|
| Adrián Enrique Jesús Palma Obispo| u202210066   |
| Paolo Del Carmen Martinez Villanueva | 202010039 |
| Jeremy Joel Quispe Andia         | u202216279   |
| Andrea Milagros Cabanillas Gora    | u202211711   |
### Marzo del 2024

### Registro de Informes

| Versión   | Fecha       | Autor      | Descripción                                                                                      | Estado    |
|-----------|-------------|------------|--------------------------------------------------------------------------------------------------|-----------|
| 1.0       |  2024/03/22| Quispe Andia, Jeremy Joel | Creación del documento de trabajo en formato markdown. | Completo  |
| 1.1       |  2024/03/22    | Cabanillas Gora, Andrea Milagros|ante la fase de diseño, arquitectura propuesta y diseños de interfaz.               | Completo  |
| 1.2       |  2024/03/22    | Adrián Palma |implementación de funcionalidades, obstáculos encontrados y decisiones tomadas.     | En Proceso|
| 1.3       |  2024/03/22    | |de la entrega final del proyecto, implementación completa y pruebas realizadas.    | Pendiente |


### Project Report Collaboration Insights




### Tabla de contenidos
- [Capítulo I: Introducción](#cap%C3%ADtulo-i-introducci%C3%B3n)
- [Capítulo II: Requirements Elicitation & Analysis](#cap%C3%ADtulo-ii-requirements-elicitation--analysis)
- [Capítulo III: Requirements Specification](#cap%C3%ADtulo-iii-requirements-specification)
- [Capítulo IV: Product Design](#cap%C3%ADtulo-iv-product-design)
- [Capítulo V: Product Implementation, Validation & Deployment](#cap%C3%ADtulo-v-product-implementation-validation--deployment)

### Studen Outcome


| Criterio específico | Acciones Realizadas | Conclusiones |
|---------------------|----------------------|--------------|
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software. | 2024/03/22 | |
| Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software. | 2024/03/22 | |

### Capítulo I: Introducción
- 1.1. Startup Profile
  - 1.1.1. Descripción de la Startup

  - 1.1.2. Perfiles de integrantes del equipo
- 1.2. Solution Profile
  - 1.2.1. Antecedentes y problemática
  - 1.2.2. Lean UX Process
    - 1.2.2.1. Lean UX Problem Statements
    - 1.2.2.2. Lean UX Assumptions
    - 1.2.2.3. Lean UX Hypothesis Statements
    - 1.2.2.4. Lean UX Canvas
- 1.3. Segmentos objetivo
    

### Capítulo II: Requirements Elicitation & Analysis

  - 2.1.1. Análisis competitivo
  - LeetCode: Es una plataforma en línea para que los programadores practiquen sus habilidades de codificación a través de una amplia gama de preguntas de entrevistas técnicas.
Ofrece una variedad de preguntas clasificadas por dificultad y tema, así como discusiones comunitarias y soluciones para cada pregunta y proporciona una amplia gama de recursos gratuitos y opciones de suscripción premium para acceder a contenido adicional y características avanzadas.

HackerRank: Es una plataforma para que los programadores mejoren sus habilidades de codificación y se preparen para entrevistas técnicas.
Ofrece desafíos de codificación en línea, tutoriales y entrevistas prácticas, así como una comunidad activa de desarrolladores, por otro lado colabora con empresas de tecnología para ofrecer oportunidades de reclutamiento a través de la plataforma, conectando a los usuarios con empleadores potenciales.

InterviewBit Es una plataforma diseñada para ayudar a los programadores a prepararse para entrevistas técnicas en empresas de tecnología.
Ofrece una combinación de preguntas de entrevistas prácticas, tutoriales y sesiones de práctica en vivo con expertos y colabora con empresas de tecnología para ofrecer contenido exclusivo y oportunidades de reclutamiento para los usuarios de la plataforma.

        
  - 2.1.2. Estrategias y tácticas frente a competidores

<table><tr><th colspan="2" valign="top">Nombre</th><th valign="top"><b>GetWork</b></th><th valign="top">LeetCode</th><th valign="top">HackerRank</th><th valign="top">InterviewBit</th></tr>
<tr><td rowspan="2" valign="top">Perfil</td><td valign="top">Overview</td><td valign="top">Es una plataforma que ofrece recursos y entrenamiento para ayudar a los programadores a prepararse para entrevistas técnicas. </td><td valign="top">Es una plataforma en línea para codificar la preparación de entrevistas. El servicio proporciona problemas algorítmicos y de codificación destinados a que los usuarios practiquen la codificación.</td><td valign="top">HackerRank es una empresa de tecnología que se enfoca en desafíos de programación competitivos tanto para consumidores como para empresas. Los desarrolladores compiten escribiendo programas de acuerdo con las especificaciones proporcionadas</td><td valign="top">Es una plataforma para aprender las habilidades que necesita para trabajos tecnológicos. Le ayudamos a pulir sus habilidades y prepararse para el trabajo, ya sea un recién graduado universitario o un profesional en activo</td></tr>
<tr><td valign="top">Ventaja competitiva ¿Que valor ofrecemos a los clientes?</td><td valign="top"><p>La plataforma podría incluir preguntas frecuentes de entrevistas, ejercicios de codificación práctica, simulacros de entrevistas en vivo con expertos y tutoriales sobre temas comunes de entrevistas. Además, tendriamos empresas de tecnología para ofrecer contenido exclusivo y oportunidades de reclutamiento para los usuarios de la plataforma. Ofrecemos membresías premium que brindan acceso a contenido adicional, sesiones de tutoría personalizada y garantías de devolución de dinero para aquellos que no logren resultados satisfactorios en sus entrevistas.</p><p></p></td><td valign="top">ofrece una plataforma integral que combina preguntas de codificación práctica, discusiones comunitarias, entrenamiento para entrevistas técnicas y características avanzadas para ayudar a los desarrolladores a mejorar sus habilidades de codificación y prepararse para entrevistas en empresas de tecnología</td><td valign="top">ofrece una plataforma integral que combina desafíos de codificación, entrenamiento para entrevistas técnicas, eventos de programación, certificaciones de habilidades técnicas y herramientas de análisis para ayudar a los desarrolladores a mejorar sus habilidades y avanzar en sus carreras en tecnología.</td><td valign="top">InterviewBit ofrece a sus clientes una plataforma integral para prepararse para entrevistas técnicas, mejorar sus habilidades de programación, recibir orientación profesional y acceder a oportunidades laborales en la industria tecnológica.</td></tr>
<tr><td valign="top">Plan de marketing</td><td valign="top">Mercado objetivo</td><td valign="top">El mercado objetivo serían programadores y profesionales de tecnología que estén buscando empleo en empresas del sector tecnológico. Este mercado incluiría a estudiantes universitarios de carreras relacionadas con la informática, ingeniería informática o campos afines, así como a profesionales con experiencia que estén buscando cambiar de trabajo o avanzar en sus carreras dentro de la industria tecnológica.</td><td valign="top"><p>Candidatos en búsqueda de empleo</p><p>Empresas que buscan contratar empleados</p></td><td valign="top"><p>Desarrolladores, entusiastas de la programación</p><p>Reclutadores  empresas en busca de talento tecnológico</p><p>interesados en mejorar sus habilidades de programación, prepararse para entrevistas técnicas y encontrar oportunidades laborales en el campo de la tecnología.</p></td><td valign="top"><p>estudiantes y profesionales de tecnología que buscan mejorar sus habilidades de codificación y prepararse para entrevistas técnicas </p><p></p><p></p><p></p><p></p><p></p></td></tr>
<tr><td valign="top"> </td><td valign="top">Estrategias de Marketing</td><td valign="top">se utilizarían tácticas de publicidad en línea, marketing de influencia y asociaciones estratégicas con instituciones educativas y empresas de tecnología. El email marketing y la construcción de una comunidad en torno a la plataforma también serían componentes importantes para mantener a los usuarios comprometidos y fomentar la participación. </td><td valign="top">LeetCode utiliza diversas estrategias de marketing y publicidad en línea para promocionar su plataforma y llegar a nuevos usuarios. Esto puede incluir anuncios pagados en motores de búsqueda, redes sociales, sitios web relacionados con la tecnología y otras plataformas en línea.</td><td valign="top">El plan de marketing para HackerRank se enfoca en comprender a su audiencia objetivo, destacar sus propuestas únicas de venta y utilizar diversas estrategias de marketing para alcanzar los objetivos establecidos. Esto incluye la creación de contenido relevante, el uso de redes sociales, SEO, email marketing, alianzas estratégicas, publicidad pagada y participación en eventos. Se asigna un presupuesto y recursos para cada estrategia, seguido de una implementación cuidadosa, monitoreo constante de resultados y ajustes según sea necesario. El plan se centra en la mejora continua y la innovación para mantener a HackerRank competitivo y atraer a más usuarios y clientes.</td><td valign="top">Las estrategias de marketing para InterviewBit se centran en la creación de contenido educativo de alta calidad, publicidad digital dirigida en plataformas relevantes, optimización para motores de búsqueda (SEO), campañas de email marketing, alianzas estratégicas con instituciones educativas y empresas de tecnología, marketing de influencers, eventos y webinars, y programas de referidos. Estas estrategias tienen como objetivo aumentar la visibilidad de InterviewBit, atraer nuevos usuarios y construir una comunidad comprometida de aprendices de tecnología.</td></tr>
<tr><td rowspan="3" valign="top">Perfil del producto</td><td valign="top">Productos y Servicios</td><td valign="top"><p>Recursos educativos</p><p>Simulacros de entrevistas en vivo</p><p>contenido exclusivo y oportunidades de reclutamiento</p><p>Membresías premium</p></td><td valign="top"><p>Plataforma de práctica de codificación</p><p>Banco de preguntas de entrevista</p><p>Contenido educativo</p><p>Premium Membership</p></td><td valign="top"><p>Plataforma de Desafíos de Codificación</p><p>Herramientas de Entrevistas Técnicas</p><p>Plataforma de Contratación Técnica:</p><p>Desafíos de Codificación en el Mundo Real</p></td><td valign="top"><p>Plataforma de Aprendizaje</p><p>Preparación para Entrevistas Técnicas</p><p>Evaluación de Habilidades Técnicas</p><p>Recursos Educativos</p></td></tr>
<tr><td valign="top">Precios y Costos</td><td valign="top">Membresías premium:  $9.99</td><td valign="top"><p>Membresía premium cuesta:</p><p>Plan mensual: Aproximadamente $35 USD por mes.</p><p>Plan anual: Aproximadamente $159 USD por año.</p></td><td valign="top"><p></p><p>Starter : 1 user $100</p><p>Pro : 5 user $450</p><p></p></td><td valign="top">El precio depende del plan que quieras dependiendo de que a empresas quieres postular y cuanto tiempo dura la preparación.</td></tr>
<tr><td valign="top">Canales de distribución</td><td valign="top">Sus canales de distribución serian  la propia plataforma en línea, redes sociales, publicidad en línea, marketing de contenidos, marketing de afiliados, email marketing, asociaciones estratégicas y participación en eventos. Estos canales se utilizan para aumentar la visibilidad, llegar a una amplia audiencia y atraer a usuarios interesados en mejorar sus habilidades técnicas para entrevistas en la industria tecnológica.</td><td valign="top"><p>Los canales de distribución de LeetCode se centran principalmente en su plataforma en línea, a través de la cual los usuarios pueden acceder a sus productos y servcios.</p><p>El canal principal de distribución de LeetCode es su plataforma en línea, que está accesible a través de su sitio web oficial</p><p>LeetCode ofrece aplicaciones móviles disponibles para dispositivos iOS y Android.</p><p></p><p></p></td><td valign="top">HackerRank utiliza una combinación de canales en línea, estrategias de marketing digital, alianzas estratégicas y ventas directas para distribuir sus servicios a usuarios individuales y empresas en el campo de la tecnología y la contratación técnica</td><td valign="top"><p>Los canales de distribución de InterviewBit se centran en la distribución de sus servicios a través de una plataforma en línea, su sitio web oficial y diversas estrategias de marketing digital, incluyendo SEO, marketing de contenidos y redes sociales. Además, la empresa puede aprovechar alianzas estratégicas con instituciones educativas y empresas de tecnología, así como implementar programas de afiliados para ampliar su alcance. Estos canales de distribución permiten a InterviewBit llegar a su audiencia objetivo y promocionar sus servicios de manera efectiva en el mercado.</p><p></p><p></p><p></p><p></p><p></p><p></p></td></tr>
<tr><td rowspan="4" valign="top">Análisis SWOT</td><td valign="top">Fortalezas</td><td valign="top"><p>Contenido diverso y útil: La plataforma ofrece una amplia gama de recursos educativos, simulacros de entrevistas en vivo y contenido exclusivo, lo que la hace atractiva para los usuarios que buscan prepararse para entrevistas técnicas en empresas de tecnología.</p><p></p><p>Colaboraciones estratégicas: Las asociaciones con empresas de tecnología y otras organizaciones relevantes proporcionan acceso a contenido exclusivo y oportunidades de reclutamiento, lo que añade valor a la plataforma y la diferencia de la competencia.</p><p></p><p>Variedad de canales de distribución: Utiliza una combinación efectiva de canales de distribución en línea y fuera de línea, lo que permite llegar a una amplia audiencia de manera eficiente y efectiva.</p></td><td valign="top">Las fortalezas de LeetCode incluyen su amplia colección de problemas, plataforma fácil de usar, contenido educativo complementario, enfoque en la preparación para entrevistas técnicas, comunidad activa y opciones de membresía premium. Estas características hacen que LeetCode sea una herramienta valiosa para programadores de todos los niveles que buscan mejorar sus habilidades de codificación y prepararse para desafíos profesionales en el campo de la tecnología.</td><td valign="top"><p>HackerRank destaca por su amplia oferta de desafíos de codificación, herramientas de preparación para entrevistas técnicas, soluciones de contratación técnica para empresas, enfoque en proyectos del mundo real y recursos educativos, lo que lo convierte en una plataforma integral para desarrolladores y empresas en el campo de la tecnología.</p><p></p><p></p><p></p><p></p><p></p><p></p></td><td valign="top"><p>Plataforma educativa integral con recursos de calidad para mejorar las habilidades de programación.</p><p>Enfoque en la preparación para entrevistas técnicas, una necesidad creciente en el mercado laboral de tecnología.</p><p>Capacidad para adaptarse a las tendencias tecnológicas y ofrecer contenido actualizado y relevante.</p><p>Amplia gama de recursos educativos disponibles para usuarios de diversos niveles de habilidad</p></td></tr>
<tr><td valign="top">Oportunidades</td><td valign="top"><p>Crecimiento del mercado de tecnología: Con el continuo crecimiento del sector tecnológico, hay una creciente demanda de herramientas y recursos para ayudar a los profesionales a prepararse para entrevistas técnicas, lo que representa una oportunidad de crecimiento para la plataforma.</p><p></p><p>Expansión internacional: Existe la posibilidad de expandir la plataforma a mercados internacionales, aprovechando la demanda global de preparación para entrevistas técnicas en empresas de tecnología.</p></td><td valign="top">Las oportunidades para LeetCode son amplias y pueden incluir la expansión de la plataforma, el desarrollo de contenido educativo, el enfoque en la educación académica, la personalización de la experiencia del usuario, la internacionalización y las colaboraciones estratégicas. Al aprovechar estas oportunidades, LeetCode puede continuar creciendo y mejorando su oferta para satisfacer las necesidades cambiantes de los usuarios en el campo de la programación y la tecnología.</td><td valign="top">HackerRank tiene la oportunidad de capitalizar el crecimiento del mercado de tecnología, la educación en línea, la digitalización de procesos de contratación, la expansión internacional y las alianzas estratégicas para seguir creciendo y consolidándose como una plataforma líder en el campo de la tecnología y la contratación técnic</td><td valign="top"><p>Crecimiento continuo del mercado de tecnología y demanda de habilidades técnicas.</p><p>Aumento de la educación en línea y la preparación para entrevistas técnicas.</p><p>Posibilidad de expandirse a nuevos mercados internacionales y colaborar con instituciones educativas.</p><p>Potencial para establecer alianzas estratégicas y programas de afiliados para ampliar el alcance y la visibilidad.</p></td></tr>
<tr><td valign="top">Debilidades</td><td valign="top"><p>Competencia intensa: El mercado de preparación para entrevistas técnicas está saturado, con múltiples competidores ofreciendo servicios similares, lo que puede dificultar la diferenciación y la captación de usuarios.</p><p></p><p></p><p>Dependencia de asociaciones: La plataforma puede depender en gran medida de asociaciones estratégicas con empresas de tecnología, lo que podría limitar su crecimiento si estas asociaciones se ven afectadas.</p></td><td valign="top"><p></p><p>Las debilidades que tiene son : </p><p>Curva de aprendizaje pronunciada, lo que puede resultar intimidante para principiantes.</p><p>Retroalimentación limitada sobre soluciones propuestas por usuarios.</p><p>Falta de diversidad en el contenido, especialmente en áreas especializadas.</p><p>Costo elevado de la membresía premium, lo que limita el acceso a características clave.</p><p>Dependencia excesiva en la resolución de problemas específicos, limitando la comprensión más amplia de conceptos.</p><p>Limitaciones en la colaboración y la interacción entre usuarios.</p></td><td valign="top"><p>HackerRank puede enfrentar desafíos en términos de competencia en el mercado, percepción de complejidad de la plataforma, limitaciones de personalización y dependencia de habilidades técnicas, lo que podría afectar su capacidad para mantener y expandir su base de usuarios.</p><p></p><p></p><p></p><p></p><p></p><p></p></td><td valign="top"><p>Competencia en el mercado de plataformas educativas y de preparación para entrevistas técnicas.</p><p>Posible complejidad percibida de la plataforma para algunos usuarios.</p><p>Limitaciones en la personalización de la experiencia del usuario.</p><p>Dependencia de habilidades técnicas y entrevistas técnicas puede limitar el atractivo para audiencias no técnicas.</p></td></tr>
<tr><td valign="top">Amenazas</td><td valign="top">Cambios en las tendencias tecnológicas: Los cambios rápidos en la tecnología pueden hacer que ciertos recursos y habilidades se vuelvan obsoletos, lo que podría afectar la relevancia de la plataforma si no se adapta rápidamente.</td><td valign="top">LeetCode enfrenta varias amenazas en su posición en el mercado de aprendizaje de programación, que incluyen la competencia creciente, cambios en la demanda del mercado, problemas de calidad del contenido, preocupaciones de ciberseguridad y privacidad.</td><td valign="top">HackerRank enfrenta amenazas potenciales como la competencia en el mercado, los cambios tecnológicos, las regulaciones de protección de datos, las amenazas de seguridad cibernética y las condiciones económicas adversas, que podrían impactar su capacidad para mantener y expandir su base de usuarios.</td><td valign="top"><p>Competencia continua y evolución del mercado de tecnología y educación en línea. Cambios en las tecnologías y programación pueden requerir actualizaciones frecuentes de contenido.Posibles cambios en las regulaciones de privacidad de datos pueden afectar la recopilación y el uso de información de los usuarios.</p><p></p></td></tr>
</table>


- 2.2. Entrevistas
- Las entrevistas van dirigidas a desarrolladores, estudiantes y programadores ya que son el público objetivo principal de la plataforma, entrevistarlos permitirá comprender sus necesidades específicas en términos de preparación para entrevistas técnicas, qué recursos encuentran más útiles, qué áreas considera más desafiantes y qué características valorarán en la plataforma.

  - 2.2.1. Diseño de entrevistas
 ¿Cuáles son los mayores desafíos que enfrentas al prepararte para entrevistas técnicas en empresas de tecnología?

¿Qué recursos o plataformas has utilizado anteriormente para prepararte para entrevistas técnicas? ¿Qué aspectos de estos recursos te resultaron más útiles y qué aspectos consideras que podrían mejorarse?

¿Qué tipo de características consideras esenciales en una plataforma de preparación para entrevistas técnicas? 

¿Qué tan importante crees que es la práctica de codificación en tiempo real para prepararte para entrevistas técnicas? ¿Has tenido experiencia previa con simulacros de entrevistas en vivo?

¿Qué áreas específicas de conocimiento técnico crees que son más importantes para destacarte en una entrevista técnica?

¿Has tenido alguna experiencia en la que la preparación para entrevistas técnicas te ayudo a entrar a un trabajo? Si es así, ¿puedes compartir esa experiencia?

¿Qué te gustaría ver en un contenido exclusivo en una plataforma de preparación para entrevistas técnicas?

¿Considerarías pagar por una membresía premium en una plataforma de preparación para entrevistas técnicas? ¿Qué características o beneficios te convencerán de hacerlo?

¿Hay algún aspecto particular sobre el proceso de preparación para entrevistas técnicas que creas que a menudo se pasa por alto pero que es crucial para el éxito?

- 2.2.2. Registro de entrevistas

| Entrevistado N°1: Andrés Valle | <img src="URL_DE_LA_IMAGEN" alt="image" width="40" height="40"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Andrés Valle                                               |
| **Edad:**                      | 32                                                         |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Ingeniero Aeronáutico                                      |
| **Entrevista:**                | [Link](https://www.youtube.com/watch?v=DpATSL0ElpE)       |
| **Momento de inicio:**         | 0:04                                                       |
| **Duración:**                  | 3:50                                                       |


| Entrevistado N°2: Marcelo Poggi | <img src="URL_DE_LA_IMAGEN" alt="image" width="40" height="40"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Marcelo Poggi                                             |
| **Edad:**                      | 20                                                        |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | ciencias de la computacion                                     |
| **Entrevista:**                | [Link]( https://s21.aconvert.com/convert/p3r68-cdx67/upbbj-6fgmc.mp4) |
| **Momento de inicio:**         | 0:05                                                       |
| **Duración:**                  | 7:32                                                       |


| Entrevistado N°3: Alex Avila | <img src="URL_DE_LA_IMAGEN" alt="image" width="40" height="40"> |
|--------------------------------|------------------------------------------------------------|
| **Nombre:**                    | Alex Avila                                             |
| **Edad:**                      | 19                                                       |
| **Sexo:**                      | Masculino                                                  |
| **Ocupación:**                 | Estudiante de ingieniria de software                                 |
| **Entrevista:**                | [Link](  https://s17.aconvert.com/convert/p3r68-cdx67/p74mx-5ve2z.mp4) |
)       |
| **Momento de inicio:**         | 0:05                                                       |
| **Duración:**                  | 6:40                                                      |

























- 2.2.3. Análisis de entrevistas







- 2.3. Needfinding
- 2.3.1. User Personas
  
  Segmento objetivo 1: Leticia Cassanova
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/e9cf2616-00fc-422a-9803-0abbff8c61e6)
  
  Segmento objetivo 2: Maria Sanchez
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/c328dcbf-3e6a-4b07-8ca3-6ccd5d8034f0)

  
  
- 2.3.2. User Task Matrix
Segmento objetivo 1: Leticia Cassanova

| Actividades                                                                                               | Frecuencia     | Importancia |
|-----------------------------------------------------------------------------------------------------------|----------------|-------------|
| Acceder a recursos de preparación para entrevistas técnicas en línea.                                     | Con Frecuencia | Alta        |
| Participar en simulacros de entrevistas técnicas en vivo.                                                  | Con Frecuencia | Alta        |
| Realizar ejercicios de codificación práctica para mejorar habilidades técnicas.                            | Con Frecuencia | Alta        |
| Almacenar y organizar documentos relacionados con oportunidades laborales y proyectos en la nube.         | A veces        | Media       |
| Acceder a material de estudio y tutoriales para mejorar habilidades de codificación.                        | Con Frecuencia | Alta        |
| Valorar la privacidad y seguridad en el acceso y almacenamiento de datos personales y laborales.          | Siempre         | Muy Alta    |
| Utilizar herramientas colaborativas en línea para proyectos grupales o trabajo remoto.                     | Con Frecuencia | Alta        |
| Participar en comunidades en línea para obtener retroalimentación y consejos sobre búsqueda de empleo.    | A veces        | Media       |
| Actualizarse sobre tendencias y noticias del mercado laboral y tecnológico.                                | Con Frecuencia | Alta        |

Segmento objetivo 2: Maria Sanchez

| Actividades                                                                                               | Frecuencia       | Importancia |
|-----------------------------------------------------------------------------------------------------------|------------------|-------------|
| Acceder a recursos de preparación para entrevistas técnicas en línea.                                     | Con Frecuencia   | Alta        |
| Participar en simulacros de entrevistas técnicas en vivo.                                                  | Con Frecuencia   | Alta        |
| Realizar ejercicios de codificación práctica para mejorar habilidades técnicas.                            | Con Frecuencia   | Alta        |
| Almacenar y organizar documentos relacionados con oportunidades laborales y proyectos en la nube.         | A veces          | Media       |
| Acceder a material de estudio y tutoriales para mejorar habilidades de codificación.                       | Con Frecuencia   | Alta        |
| Valorar la privacidad y seguridad en el acceso y almacenamiento de datos personales y laborales.          | Siempre          | Muy Alta    |
| Utilizar herramientas colaborativas en línea para proyectos grupales o trabajo remoto.                     | Con Frecuencia   | Alta        |
| Participar en comunidades en línea para obtener retroalimentación y consejos sobre búsqueda de empleo.    | A veces          | Media       |
| Actualizarse sobre tendencias y noticias del mercado laboral y tecnológico.                                | Con Frecuencia   | Alta        |


- 2.3.3. User Journey Mapping
  

- 2.3.4. Empathy Mapping

  Segmento objetivo 1: Leticia Cassanova
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/21a6b83d-675b-4cf9-bfca-103064d65287)

  Segmento objetivo 2: Maria Sanchez

  
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/258d5100-da3e-4198-8497-c4eea2ff7418)

- 2.3.5. As-is Scenario Mapping


- 2.4. Ubiquitous Language

### Capítulo III: Requirements Specification
- 3.1. To-Be Scenario Mapping
- 3.2. User Stories
- 3.3. Impact Mapping
- 3.4. Product Backlog

### Capítulo IV: Product Design
- 4.1. Style Guidelines
  - 4.1.1. General Style Guidelines
  - 4.1.2. Web Style Guidelines
- 4.2. Information Architecture
- 4.2.1. Organization Systems

- 4.2.2. Labeling Systems


- 4.2.3. SEO Tags and Meta Tags
- 4.2.4. Searching Systems
- 4.2.5. Navigation Systems
- 4.3. Landing Page UI Design
  - 4.3.1. Landing Page Wireframe
  - 4.3.2. Landing Page Mock-up
- 4.4. Web Applications UX/UI Design
  - 4.4.1. Web Applications Wireframes
  - 4.4.2. Web Applications Wireflow Diagrams
  - 4.4.3. Web Applications Mock-ups
  - 4.4.4. Web Applications User Flow Diagrams
- 4.5. Web Applications Prototyping
- 4.6. Domain-Driven Software Architecture
  - 4.6.1. Software Architecture Context Diagram
  - 4.6.2. Software Architecture Container Diagrams
  - 4.6.3. Software Architecture Components Diagrams
- 4.7. Software Object-Oriented Design
  - 4.7.1. Class Diagrams


  - 4.7.2. Class Dictionary


- 4.8. Database Design


  - 4.8.1. Database Diagram



### Capítulo V: Product Implementation, Validation & Deployment
- 5.1. Software Configuration Management
  - 5.1.1. Software Development Environment Configuration
  - 5.1.2. Source Code Management
  - 5.1.3. Source Code Style Guide & Conventions
  - 5.1.4. Software Deployment Configuration
- 5.2. Landing Page, Services & Applications Implementation
  - 5.2.X. Sprintn
    - 5.2.X.1. Sprint Planningn
    - 5.2.X.2. Sprint Backlogn
    - 5.2.X.3. Development Evidence for Sprint Review
    - 5.2.X.4. Testing Suite Evidence for Sprint Review
    - 5.2.X.5. Execution Evidence for Sprint Review
    - 5.2.X.6. Services Documentation Evidence for Sprint Review
    - 5.2.X.7. Software Deployment Evidence for Sprint Review
    - 5.2.X.8. Team Collaboration Insights during Sprint

**Conclusiones**
- Conclusiones y recomendaciones
- Video About-the-Team
**Bibliografía**

**Anexos**



