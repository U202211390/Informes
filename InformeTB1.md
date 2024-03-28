# Universidad Peruana de Ciencias Aplicadas
### INFORME DEL TRABAJO 1 (TB1)
![image](https://github.com/TripTeamOrganization/Informes/assets/134337719/c8a24a74-515a-436b-b7b9-ea1b2e418e60)

**Curso:** Aplicaciones Web

**Sección:** SW56

**Profesor:** Efraín Ricardo Bautista Ubillús

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
 
    *CodePace* es una plataforma especializada en la preparación de programadores para entrevistas técnicas en empresas de tecnología. Nos dedicamos a ofrecer una variedad de recursos y entrenamiento diseñados para ayudar a los usuarios a mejorar sus habilidades de                 codificación, prepararse para entrevistas y asegurar trabajos en la industria tecnológica.

    Con un enfoque centrado en el usuario, nuestra plataforma proporciona una experiencia integral que abarca desde preguntas frecuentes de entrevistas hasta ejercicios de codificación práctica y simulacros de entrevistas en vivo con expertos. Además, colaboramos                  estrechamente con empresas de tecnología para ofrecer contenido exclusivo y oportunidades de reclutamiento para nuestros usuarios.

    **Misión:**
    Nuestra misión en CodePace es brindar a los programadores las herramientas y el conocimiento necesarios para tener éxito en sus entrevistas técnicas y carreras profesionales en la industria tecnológica. Nos esforzamos por ser el compañero de confianza de cada usuario en       su viaje hacia el éxito laboral en tecnología.

    **Visión:**
    En *CodePace*, visualizamos un futuro donde cada programador tenga acceso a recursos de calidad y entrenamiento efectivo para prepararse para entrevistas técnicas y avanzar en sus carreras en la industria tecnológica. Nos dedicamos a ser líderes en la preparación para         entrevistas técnicas, impulsando el crecimiento y la excelencia en la comunidad de desarrolladores a nivel mundial.


  - 1.1.2. Perfiles de integrantes del equipo

| Integrantes                        | Descripción del perfil |
|-----------------------------------|--------------|
|Elias Yauri Paucar (u202211817)<br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/7cc1bfac-2b67-43eb-bb3a-140739bb4b8c" alt="Elias Yauri" style="width: 200px;">|Mi nombre es Elias Yauri Paucar, tengo 18 años, soy estudiante de Ing. De software en la UPC y actualmente estoy en 5 ciclo de mi carrera. Me considero una persona muy versátil a cualquier circunstancia o problema que se me presente, me logro acoplar y congeniar fácilmente con un equipo. Me comprometo a dar mi mayor esfuerzo en realizar todos los puntos y actividades con respecto a este proyecto.|
| Jair Castillo (u202211390)<br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/f96f45ff-da0d-4adf-b7a8-92382705d282" alt="Jair Castillo" style="width: 200px;">|Mi nombre es Jair Castillo, estoy cursando el 5to ciclo de la carrera de Ingeniería de Software en la UPC.Poseo habilidades intermedias en el lenguaje de programación C++. Soy una persona atenta y responsable, con capacidad para adaptarme de manera efectiva a diversos escenarios y desafíos que puedan surgir.|
| Jeremy Joel Quispe Andia (u202216279) <br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/8640c1f6-2922-480b-88d3-be4f0a8ec94f" alt="Jeremy Quispe" style="width: 200px;"> |Mi nombre es Jeremy Quispe, estoy cursando el 5to ciclo de la carrera de Ingeniería de Software en la UPC. Decidí estudiar esta carrera debido a que me agrada mucho poder crear soluciones tecnológicas y cómo estás podrían contribuir de manera positiva a la sociedad. Por ello, agradezco a la universidad por brindarme los recursos para poder superarme cada día y adquiriendo grandes conocimientos.|
| Andrea Milagros Cabanillas Gora (u202211711) <br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/f800cd02-e527-4056-9807-e61dbacd264b" alt="Andrea Cabanillas" style="width: 200px;">| Soy Andrea, actualmente soy una estudiante de Ingeniería de software, me gusta diseñar paginas web, dibujar y bailar marinera.   |
| Sebastian Nicolas Cachis Gonzales (u202210846) <br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/552d3d92-0a4d-41d8-b90e-3ec504d56c55" alt="Sebastian Cachis" style="width: 200px;">| Tengo 19 años, soy alumno de Ingeniería de Software en la UPC en mi quinto ciclo. Me considero una persona proactiva, organizada, meticulosa y muy enfocada en mis estudios, tanto grupales como individuales. Tengo facilidad para entender y ejemplificar los distintos temas que vemos, teniendo soltura para explicar.  |
| Adriano Sebastian Cruz Palomino (u202211711) <br><img src="https://github.com/CodepaceOrganization/Informes/assets/134337719/4ea280b1-1aa7-485f-ab81-05404307bf22" alt="Adriano Cruz" style="width: 200px;">|Mi nombre es Adriano Sebastian Cruz Palomino, tengo 19 años, soy alumno de Ingeniería de Software en la UPC, actualmente estoy cursando el 5to ciclo. Soy una persona curiosa, responsable, y comprometida con mis estudios, siempre busco aprender más y mejorar mis habilidades.  |
- 1.2. Solution Profile
  - 1.2.1. Antecedentes y problemática
  
    Para comprender las necesidades de nuestros usuarios universitarios en el proyecto GetWork, hemos realizado un estudio utilizando la técnica 5W's & 2H's. Esta metodología, ampliamente utilizada en la gestión empresarial, nos ha permitido identificar los siguientes             aspectos cruciales:

    **¿Cuáles son las 5W?**
    What (Qué)

    El problema que abordamos es la falta de preparación adecuada de los estudiantes universitarios para enfrentarse a entrevistas técnicas y el mercado laboral en el ámbito de la tecnología. Muchos graduados carecen de las habilidades técnicas, de resolución de problemas y       de comunicación necesarias para destacar en este competitivo campo. La insuficiente preparación limita sus oportunidades laborales y puede afectar negativamente su progreso profesional.

    **Who (Quién)**

    Este problema afecta a estudiantes universitarios de diversas disciplinas y niveles académicos que aspiran a ingresar al mercado laboral tecnológico. Tanto profesores como estudiantes se ven directamente afectados por la falta de preparación para enfrentar las exigencias      específicas de la industria.

    **When (Cuándo)**

    El problema se manifiesta en el momento en que los estudiantes universitarios están buscando oportunidades laborales y se enfrentan a entrevistas técnicas. La falta de preparación adecuada puede hacer que pierdan oportunidades valiosas de empleo y retrasar su inserción en     el mercado laboral.

    **Where (Dónde)**

    El problema está presente en todo el proceso de búsqueda de empleo, desde la elaboración de currículums hasta la participación en entrevistas, tanto en entornos físicos como virtuales. La falta de habilidades técnicas y de preparación puede obstaculizar la capacidad de        los estudiantes para destacar en cualquier contexto laboral.

    **Why (Por qué)**

    La causa fundamental del problema radica en la falta de acceso a recursos y entrenamiento especializado que prepare a los estudiantes universitarios para las demandas específicas del mercado laboral tecnológico. Aunque las instituciones educativas pueden brindar una base      sólida en conceptos teóricos, muchas veces no ofrecen una preparación práctica y específica para las habilidades y competencias necesarias en la industria.

    **¿Cuáles son las 2H?**
    **How (Cómo)**

    Nuestros usuarios recurren a GetWork cuando desean mejorar sus habilidades técnicas, prepararse para entrevistas técnicas y asegurar empleos en la industria tecnológica. Descubren nuestra plataforma a través de campañas de promoción en línea, recomendaciones de amigos, y      referencias de instituciones educativas y empresas asociadas. GetWork ofrece una amplia gama de recursos y herramientas, incluyendo preguntas frecuentes de entrevistas, ejercicios de codificación práctica, simulacros de entrevistas en vivo con expertos, tutoriales sobre       temas comunes de entrevistas y contenido exclusivo proporcionado por empresas de tecnología.

    **How much (Cuánto)**

    En la actualidad, el mercado laboral tecnológico experimenta un crecimiento constante y una demanda creciente de profesionales con habilidades técnicas sólidas. Se espera que esta tendencia continúe en los próximos años, lo que respalda la importancia y la viabilidad de       plataformas como GetWork. El volumen de datos almacenados en la nube sigue aumentando exponencialmente, reflejando la necesidad continua de soluciones seguras y confiables para la preparación laboral en tecnología. Este crecimiento y demanda ofrecen un amplio campo de          oportunidades para la expansión y el desarrollo futuro de GetWork.

    - 1.2.2. Lean UX Process

    El proceso Lean UX Process es una estrategia diseñada para optimizar el desarrollo de nuestro producto, centrándose en principios esenciales como la validación, el pensamiento y la acción. Siguiendo esta filosofía, hemos creado nuestro propio proceso Lean UX, que se           fundamenta en cuatro elementos clave: declaraciones de problemas, suposiciones, enunciados de hipótesis y lienzo.
    - 1.2.2.1. Lean UX Problem Statements

    Con la plataforma de preparación para entrevistas técnicas, nos enfrentamos a un desafío crítico en la seguridad de los datos y la confidencialidad de la información personal y profesional de nuestros usuarios. Es fundamental abordar esta preocupación para garantizar la       confianza de los programadores que utilizan nuestra plataforma.

    Para enfrentar esta incertidumbre y ofrecer una solución confiable, hemos desarrollado un proceso basado en la metodología Lean UX, adaptado específicamente a las necesidades de nuestro proyecto.

    En primer lugar, identificamos claramente el problema principal que enfrentan nuestros usuarios: la preocupación por la seguridad y la privacidad de sus datos mientras utilizan nuestra plataforma para prepararse para entrevistas técnicas. Esta preocupación se convierte en     nuestra declaración de problema, lo que nos permite comprender a fondo las necesidades y preocupaciones de nuestros usuarios.

    A continuación, formulamos suposiciones sobre cómo podríamos abordar este problema y mejorar la seguridad de los datos para nuestros usuarios. Estas suposiciones nos ayudan a generar hipótesis sobre las posibles soluciones que podríamos implementar para garantizar la          confidencialidad de la información personal y profesional de nuestros usuarios.

    Una vez que tenemos nuestras hipótesis, las sometemos a pruebas y validación utilizando diversas técnicas, como pruebas de penetración, auditorías de seguridad y evaluaciones de riesgos. Esto nos permite recopilar datos reales y retroalimentación de nuestros usuarios para     evaluar la efectividad de nuestras soluciones propuestas en términos de seguridad de datos.

    Finalmente, basándonos en los resultados de nuestras pruebas y validación, iteramos en nuestro diseño y ejecución para mejorar continuamente la seguridad y la confidencialidad de la información de nuestros usuarios. Esto nos permite desarrollar una plataforma de               preparación para entrevistas técnicas que nuestros usuarios puedan utilizar con total confianza en la protección de sus datos personales y profesionales.

  - 1.2.2.2. Lean UX Assumptions

  **Business Assumptions**
  
  Creemos que existe una necesidad en el mercado de una plataforma que ayude a los programadores a prepararse de manera efectiva para las entrevistas técnicas en empresas de tecnología.
  
  Esta necesidad puede ser abordada mediante el desarrollo de una plataforma que ofrezca recursos de calidad, como preguntas frecuentes de entrevistas, ejercicios de codificación práctica y simulacros de entrevistas en vivo con expertos.
  
  Nuestros clientes iniciales serán programadores y desarrolladores de software que estén buscando activamente oportunidades laborales en empresas de tecnología.
  
  El valor principal que nuestros clientes desean de nuestro servicio es poder prepararse de manera adecuada y eficiente para las entrevistas técnicas, aumentando así sus posibilidades de éxito en el proceso de contratación.
  
  Los clientes también obtendrán beneficios adicionales, como acceso a contenido exclusivo de empresas de tecnología y oportunidades de reclutamiento a través de la plataforma.
  
  Planeamos adquirir la mayoría de nuestros clientes mediante estrategias de marketing digital dirigidas a programadores y desarrolladores interesados en mejorar sus habilidades y oportunidades laborales.
  
  Generaremos ingresos a través de membresías premium que brinden acceso a contenido adicional, sesiones de tutoría personalizada y garantías de devolución de dinero para aquellos que no logren resultados satisfactorios en sus entrevistas, además de comisiones por oportunidades de reclutamiento.
  
  Nuestra competencia principal serán otras plataformas de preparación para entrevistas técnicas, así como recursos en línea disponibles gratuitamente.
  
  Nos diferenciaremos de la competencia al ofrecer contenido exclusivo de empresas de tecnología y oportunidades de reclutamiento integradas en la plataforma.
  
  El mayor riesgo para nuestro servicio es que el segmento objetivo no perciba el valor agregado de nuestra plataforma o no esté dispuesto a invertir en su preparación para entrevistas técnicas.
  
  Resolveremos este riesgo mediante una estrategia de marketing efectiva que resalte los beneficios y ventajas de nuestra plataforma, así como mediante una continua mejora y actualización de nuestro contenido y servicios.

  **User Assumptions**
  
  ¿Quién es el usuario?
  Los usuarios principales son programadores y desarrolladores de software que buscan activamente oportunidades laborales en empresas de tecnología.
  
  ¿Qué problemas enfrenta nuestro producto y cómo los resolveremos?
  Uno de los problemas actuales del producto es la posible falta de acceso a recursos de calidad para prepararse adecuadamente para las entrevistas técnicas. Esto se resolverá mediante la incorporación de contenido exclusivo de empresas de tecnología y sesiones de tutoría personalizada.
  
  ¿Qué características son importantes?
  Las características clave incluyen preguntas frecuentes de entrevistas, ejercicios de codificación práctica, simulacros de entrevistas en vivo con expertos, así como acceso a contenido exclusivo de empresas de tecnología y oportunidades de reclutamiento integradas en la plataforma.
  
  ¿Dónde encaja nuestro producto en la vida laboral del usuario?
  Nuestro producto encaja en la preparación y mejora de las habilidades de los usuarios para entrevistas técnicas, lo que aumenta sus oportunidades de obtener empleo en empresas de tecnología.
  
  ¿Cuándo y cómo se usa nuestro producto?
  El producto será utilizado cuando los usuarios estén preparándose para entrevistas técnicas en empresas de tecnología. Se accederá a la plataforma para practicar ejercicios de codificación, revisar preguntas frecuentes y participar en simulacros de entrevistas en vivo.
  
  ¿Cómo debe verse y comportarse nuestro producto?
  El producto debe tener una interfaz intuitiva y fácil de usar, con acceso rápido y sencillo a todos los recursos de preparación. Además, debe garantizar la privacidad y seguridad de los datos de los usuarios, así como ofrecer una experiencia personalizada y motivadora para el aprendizaje.


  - 1.2.2.3. Lean UX Hypothesis Statements

  **Hypothesis Statement 01:**
  **Creemos**  que los programadores y desarrolladores estarán dispuestos a adoptar nuestra plataforma de preparación para entrevistas técnicas para mejorar sus habilidades y aumentar sus posibilidades de éxito en las entrevistas de trabajo en empresas de tecnología.
  **Sabremos** que hemos tenido éxito.
  **Cuando** la tasa de adopción de la plataforma entre los usuarios objetivo alcance al menos el 80% dentro de los primeros tres meses posteriores al lanzamiento.
  
  **Hypothesis Statement 02:**
  **Creemos** que nuestra plataforma facilitará una mejor preparación para las entrevistas técnicas al proporcionar recursos de calidad y simulacros de entrevistas en vivo.
  **Sabremos** que hemos tenido éxito.
  **Cuando** se observe un aumento del 30% en la tasa de éxito de los usuarios en las entrevistas técnicas después de utilizar nuestra plataforma durante al menos un mes.
  
  **Hypothesis Statement 03:**
  **Creemos** que al ofrecer contenido exclusivo de empresas de tecnología y oportunidades de reclutamiento, nuestra plataforma aumentará la satisfacción y la confianza de los usuarios en su preparación para entrevistas técnicas.
  **Sabremos** que hemos tenido éxito.
  **Cuando** al menos el 70% de los usuarios que hayan utilizado las oportunidades de reclutamiento a través de nuestra plataforma informen haber tenido una experiencia positiva y útil.
  
  **Hypothesis Statement 04:**
  **Creemos** que al proporcionar sesiones de tutoría personalizada y garantías de devolución de dinero para aquellos que no logren resultados satisfactorios en sus entrevistas, aumentaremos la retención de usuarios y la satisfacción del cliente.
  **Sabremos** que hemos tenido éxito.
  **Cuando** la tasa de retención de usuarios de la membresía premium supere el 60% en los primeros seis meses de su lanzamiento.

  - 1.2.2.4. Lean UX Canvas

![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/8624af12-9d1f-4638-84cf-f773edc14884)

- 1.3. Segmentos objetivo

**Segmento objetivo #1: Desarrolladores en búsqueda de empleo**

Descripción: Este segmento objetivo está compuesto por programadores y desarrolladores de software que están activamente buscando oportunidades laborales en empresas de tecnología.

Aspectos demográficos:
Sexo: Masculino y Femenino
Edades: Mayoritariamente entre 18 y 35 años.
Nivel socioeconómico: Clases A, B, C (Alta, Media-alta y Media)

Aspectos geográficos:
Nacionalidad: Peruana
Zona geográfica en la que vive: Urbana
Departamento: Lima y Callao
Aspectos psicográficos:

Buscan mejorar sus habilidades técnicas para destacar en el mercado laboral.
Desean acceder a recursos de preparación para entrevistas de manera conveniente y eficaz.
Valorizan la seguridad y la privacidad en el almacenamiento de datos.
Necesidades: Buscan mejorar sus habilidades de codificación, prepararse para entrevistas técnicas y obtener un empleo en el campo tecnológico.

Requisitos: Desean una plataforma que les brinde recursos de calidad, como preguntas frecuentes de entrevistas, ejercicios de codificación práctica y simulacros de entrevistas en vivo.

Objetivo: Aumentar sus posibilidades de éxito en el proceso de contratación.

**Segmento objetivo #2: Estudiantes de informática y carreras relacionadas**

Descripción: Este segmento objetivo incluye a estudiantes universitarios y recién graduados de carreras de informática, ingeniería de software y disciplinas afines.

Aspectos demográficos:
Sexo: Masculino y Femenino
Edades: Mayoritariamente entre 18 y 25 años.
Nivel socioeconómico: Clases A, B, C (Alta, Media-alta y Media)
Aspectos geográficos:

Nacionalidad: Peruana
Zona geográfica en la que vive: Urbana
Departamento: Lima y Callao

Aspectos psicográficos:
Buscan mejorar sus habilidades técnicas y prepararse para su futura inserción laboral.
Valorizan la facilidad de acceso y la seguridad en el almacenamiento de archivos.
Prefieren soluciones intuitivas y fáciles de usar para gestionar sus documentos.
Necesidades: Están interesados en mejorar sus habilidades técnicas y prepararse para futuras entrevistas de trabajo en la industria tecnológica.

Requisitos: Buscan una plataforma que les proporcione tutoriales sobre temas comunes de entrevistas, contenido exclusivo de empresas de tecnología y oportunidades de reclutamiento.

Objetivo: Facilitar su transición al mercado laboral y obtener empleo en empresas líderes del sector tecnológico.


    

### Capítulo II: Requirements Elicitation & Analysis

  - 2.1.1. Análisis competitivo

LeetCode: Es una plataforma en línea para que los programadores practiquen sus habilidades de codificación a través de una amplia gama de preguntas de entrevistas técnicas.
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
  
Las entrevistas van dirigidas a desarrolladores, estudiantes y programadores ya que son el público objetivo principal de la plataforma, entrevistarlos permitirá comprender sus necesidades específicas en términos de preparación para entrevistas técnicas, qué recursos encuentran más útiles, qué áreas considera más desafiantes y qué características valorarán en la plataforma.

  - 2.2.1. Diseño de entrevistas


Preguntas para el Segmento Objetivo #1: Desarrolladores en búsqueda de empleo

1. ¿Qué tipo de recursos o herramientas utilizas actualmente para prepararte para entrevistas técnicas?
2. ¿Cuáles son los principales desafíos que enfrentas al prepararte para entrevistas de trabajo en empresas de tecnología?
3. ¿Qué valoras más al buscar recursos de preparación para entrevistas técnicas?
4. ¿Qué características consideras esenciales en una plataforma de preparación para entrevistas técnicas?
5. ¿Cómo te sentirías al tener acceso a preguntas frecuentes de entrevistas, ejercicios de codificación práctica y simulacros de entrevistas en vivo en una plataforma?
6. ¿Cuál es tu opinión sobre la idea de tener contenido exclusivo de empresas de tecnología en una plataforma de preparación para entrevistas?
7. ¿Qué tipo de recursos o funcionalidades crees que serían más útiles para mejorar tus habilidades técnicas y prepararte para entrevistas?
8. ¿Qué importancia le das a la seguridad y privacidad de tus datos al utilizar una plataforma de preparación para entrevistas técnicas?
9. ¿Consideras que una membresía premium que brinde acceso a contenido adicional y sesiones de tutoría personalizada sería útil para ti?
10. ¿Cómo crees que una plataforma de preparación para entrevistas técnicas podría aumentar tus posibilidades de éxito en el proceso de contratación?


Preguntas para el Segmento Objetivo #2: Estudiantes de informática y carreras relacionadas

1. ¿Qué estrategias utilizas actualmente para mejorar tus habilidades técnicas y prepararte para tu futura inserción laboral?
2. ¿Cuáles son tus mayores preocupaciones al enfrentarte al proceso de búsqueda de empleo en la industria tecnológica?
3. ¿Qué características buscas en una plataforma de preparación para entrevistas técnicas?
4. ¿Te resultaría útil tener acceso a tutoriales sobre temas comunes de entrevistas en una plataforma de preparación para entrevistas técnicas?
5. ¿Qué te parecería tener la oportunidad de acceder a contenido exclusivo de empresas de tecnología en una plataforma de preparación para entrevistas?
6. ¿Qué tipo de recursos o funcionalidades consideras más importantes para mejorar tus habilidades técnicas y prepararte para entrevistas?
7. ¿Valoras la facilidad de acceso y la usabilidad de una plataforma de preparación para entrevistas técnicas?
8. ¿Qué opinas sobre la posibilidad de tener sesiones de tutoría personalizada como parte de una membresía premium en una plataforma de preparación para entrevistas?
9. ¿Cuál es tu opinión sobre la seguridad y privacidad de tus datos al utilizar una plataforma de preparación para entrevistas técnicas?
10. ¿Cómo crees que una plataforma de preparación para entrevistas técnicas podría facilitar tu transición al mercado laboral y ayudarte a obtener empleo en empresas de tecnología líderes?

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
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/c6d2950b-7f93-4562-8f4a-7a9f089c93a9)
  
  Segmento objetivo 2: Maria Sanchez
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/3ff745a7-66bd-4319-9ff1-60104ad00ae7)

  
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
  Segmento objetivo 1: Leticia Cassanova
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/d99113c8-1dc3-4129-aafd-38589607439b)


  Segmento objetivo 2: Maria Sanchez
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/a8e6f328-6069-4355-8be1-1fe952fe34b5)


- 2.3.4. Empathy Mapping

  Segmento objetivo 1: Leticia Cassanova
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/2078dd41-9aef-4083-9147-0baebb34f5df)

  Segmento objetivo 2: Maria Sanchez

  
  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/a0b23c5e-93ad-4829-9b14-9602232c4641)

- 2.3.5. As-is Scenario Mapping

  Segmento objetivo 1: Leticia Cassanova

  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/b0ebab82-8db5-4940-816c-dcbae8207719)


  Segmento objetivo 2: Maria Sanchez

  ![image](https://github.com/CodepaceOrganization/Informes/assets/134337719/e10a7b87-9f2c-4cd3-81c4-9c140353212a)

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



