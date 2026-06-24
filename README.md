**ECORUTA ITAGUI**

**Jeronimo Trujillo Velez**

**Isamar Tamayo Villada**

**Institución Educativa Diego Echavarría Misas**

**Análisis de requisitos**

**Lora Patiño Gloria Amparo**

**Medellín, Antioquia**

**16 de junio de 2026**

Itagüí está ubicado al sur del Valle de Aburrá, en el departamento de Antioquia, Colombia. Cuenta con una población de 306,397 habitantes (Según el DANE) y cuenta con aproximadamente 350.000 vehículos a diario en sus calles, además de tener conexiones viales con otros municipios los cuales son: Medellín al norte y occidente. Envigado al oriente. Sabaneta al suroriente. La Estrella al sur y occidente. Esto hace más complejo el tema de alto flujo vehicular, ya que tiene varias conexiones con varios municipios. A continuación, se presenta una lista de los distintos vehículos que transitan en ITAGUI basada en una investigación de la alcaldía de itagui (https://itagui.gov.co/uploads/micrositios/files/2f85b-boletin-movilidad-2024.pdf?utm_source=chatgpt.com

| **Tipo** | **Estimación diaria** |
| --- | --- |
| Motocicletas | ~250.000 |
| Automóviles | ~72.000 |
| Camionetas y camperos | ~17.000 |
| Camiones de carga | ~5.000 |
| Buses y busetas | ~4.000 |
| Bicicletas y otros | ~2.000 |
| **Total** | **~350.000** |

## Situación problema

En el municipio de Itagüí, el exceso de carros, motos y camiones ha provocado que la contaminación del aire sea un problema muy grave. El tráfico pesado genera todos los días una gran cantidad de gases contaminantes y "material particulado" (que son partículas invisibles y muy dañinas que flotan en el aire y entran a nuestros pulmones), PM10 (material particulado menor a 10 micrómetros): son partículas relativamente pequeñas que pueden entrar a las vías respiratorias superiores y causar irritación, tos y problemas respiratorios. PM2.5 (material particulado menor a 2,5 micrómetros): son mucho más finas y peligrosas, ya que pueden llegar profundamente a los pulmones e incluso pasar al torrente sanguíneo, afectando el sistema respiratorio y cardiovascular. Este tipo de contaminación se categoriza por contaminación atmosférica, que es la presencia de dichas partículas solidad o liquidas suspendidas en el aire, lo que daña el medio ambiente local (Área Metropolitana del Valle de Aburrá). Estudios en la región demuestran que pasar mucho tiempo respirando este aire en los trancones aumenta las enfermedades respiratorias como el asma y los problemas del corazón (Gaviria et al., 2021). Científicos locales explican que el problema empeora en los embotellamientos de Itagüí porque los carros atrapados se quedan en "ralentí" (es decir, con el motor encendido pero sin moverse), lo que hace que contaminen el doble que cuando van directo a su destino (Bedoya & Martínez, 2022), actualmente no existe ninguna aplicación en Itagüí que le avise al ciudadano cuánta contaminación genera su viaje o cómo está el aire de su calle en tiempo real. Este problema ocurre por varias razones. La primera es que dependemos demasiado del carro o la moto particular. La segunda es la falta de "alfabetización ambiental" (que significa que las personas no conocen ni entienden el daño que causan sus hábitos). La mayoría de los conductores no sabe cuántos gases echa su carro al aire cuando está frenado en un trancón. Por último, no hay ayudas ni motivaciones claras para que la gente decida dejar el carro en casa y prefiera usar el autobús, el metro, la bicicleta o caminar en distancias cortas.

Esto trae consecuencias muy malas. Por un lado, el clima de Itagüí se vuelve más caliente y el aire es menos sano, lo que afecta las metas del planeta para frenar el cambio climático. Por el otro, las personas sufren más de estrés, cansancio y enfermedades respiratorias, afectando principalmente a los niños y a los ancianos que viven cerca de las avenidas principales.

### Alcance (¿Qué hace y qué no hace la app?)

El proyecto consiste en crear un prototipo (un modelo de prueba) de la aplicación para **Lo que SÍ incluye:** Calcular una estimación de la contaminación que genera tu viaje, avisarte con alertas si vas hacia un trancón muy contaminado, sugerirte rutas ecológicas, darte puntos virtuales de premio por contaminar menos y un espacio con lecturas sencillas para aprender sobre el cuidado del aire.

- **Lo que NO incluye:** No se conectará con las cámaras de las foto multas ni con la Secretaría de Tránsito, no usará aparatos físicos pegados al tubo de escape del carro para medir los gases, y solo funcionará dentro de nuestra región (el Valle de Aburrá).

## Estado del arte (¿Qué aplicaciones parecidas existen?)

Comparación de soluciones actuales frente a nuestro proyecto "EcoRuta Itagüí".

|     |     |     |     |
| --- | --- | --- | --- |
| **Nombre del proyecto** | **Ventajas (Lo bueno)** | **Desventajas frente a mi proyecto (Lo que le falta)** | **URL de la fuente** |
| **Waze / Google Maps** | Son mapas excelentes que millones de personas usan para ver el tráfico en vivo y encontrar caminos rápidos. | Solo les importa el tiempo. No te dicen cuánto contaminas ni les importa la calidad del aire de la ciudad. | [https://www.waze.c](https://www.waze.c/) om |
| **SIATA Mobile** | Es la aplicación oficial de la región que te muestra con colores si el aire de Itagüí está limpio o sucio usando las estaciones de monitoreo. | Es solo una pantalla con datos. No funciona como mapa para guiarte en el carro ni calcula caminos. | [https://siata.gov.co](https://siata.gov.co/) |
| **Eco Passenger** | Una página web que te compara si contamina más viajar en tren, en avión o en carro para un viaje largo. | Está hecha para Europa y para viajes entre ciudades lejanas. No sirve para los trancones del día a día en Itagüí. | [http://ecopassenger](http://ecopassenger/). org |

|     |     |     |     |
| --- | --- | --- | --- |
| **Nombre del proyecto** | **Ventajas (Lo bueno)** | **Desventajas frente a mi proyecto (Lo que le falta)** | **URL de la fuente** |
| **Changers CO2 Fit** | Una aplicación que te da premios y medallas si registras que caminaste o fuiste en bicicleta al trabajo para ahorrar contaminación. | No funciona como un GPS con mapa para el carro, por lo que no te ayuda si estás manejando en medio de un trancón. | https://www.changer s.com |

**Nuestro factor diferenciador:** Las opciones de hoy se van a los extremos: o son mapas que ignoran el medio ambiente (_Waze_) o son páginas ambientales que no te sirven como mapa (_SIATA_). **"EcoRuta Itagüí"** junta lo mejor de los dos mundos: es un mapa GPS que te guía por la ciudad, pero cuidando el aire y tu salud al mismo tiempo.

## Marco teórico

- - **Movilidad Sostenible:** Es la forma de viajar por la ciudad buscando reducir los daños al medio ambiente, por ejemplo, usando más la bicicleta, el transporte público o caminando (Organización de las Naciones Unidas \[ONU\], 2021).
    - **Huella de Carbono Vehicular:** Es la cantidad total de gases de efecto invernadero (los gases que atrapan el calor y dañan la atmósfera) que un carro expulsa por el tubo de escape al quemar gasolina o diésel.
    - **Material Particulado (PM2.5):** Son partículas de polvo, hollín y metal tan increíblemente pequeñas que flotan en el aire, no las podemos ver, pero entran directo a los pulmones y causan enfermedades. Los carros quietos en los trancones son los que más las producen.
    - **Ralentí:** Es cuando dejas el motor del carro encendido mientras estás totalmente detenido (en un semáforo o trancón). El carro sigue gastando gasolina y contaminando aunque no se mueva.
    - **Ruta Eco-Amigable:** Es un camino calculado por la aplicación que, aunque a veces no sea el más corto, evita pendientes muy altas o zonas de detenerse a cada rato, ayudando a que el carro gaste menos combustible y eche menos humo.
    - **Ciclo de Vida del Software (Pasos de Pressman):** Son las etapas ordenadas que los programadores siguen para crear una aplicación de calidad. Incluye hablar con los usuarios, planear las tareas, diseñar cómo se va a ver, programar el código, hacer pruebas de que funcione bien y finalmente lanzarla al público.

## ObjetivosObjetivo general

Crear una aplicación para celulares que ayude a los ciudadanos de Itagüí a conocer, medir y bajar la cantidad de contaminación que generan al manejar, ofreciendo rutas más limpias y premiando el uso de transportes ecológicos.

### Objetivos específicos (Organizados por las fases de desarrollo de Pressman)

1.  **Fase de Comunicación y Planeación:** Reunirse con conductores y expertos en el clima en Itagüí para escuchar qué necesidades tienen (técnicas de elicitación), anotar qué debe hacer la aplicación y organizar las fechas de trabajo.
2.  **Fase de Análisis:** Estudiar cómo se deben cruzar las matemáticas del mapa con los datos del aire para que la aplicación calcule la contaminación de forma correcta.
3.  **Fase de Diseño:** Dibujar las pantallas de la aplicación (cómo se va a ver en el celular) y diseñar la estructura interna donde se guardarán los mapas y los puntos de los usuarios.
4.  **Fase de Desarrollo (Programación):** Escribir el código en la computadora para dar vida a las funciones de la app: el mapa ecológico, el calculador de gases, las alertas de aire sucio y la entrega de puntos de premio.
5.  **Fase de Pruebas:** Salir a las calles principales de Itagüí con el celular en la mano para ensayar la aplicación con usuarios reales, asegurando que las alertas avisen a tiempo y la aplicación no se cierre sola.
6.  **Fase de Implementación y Evaluación:** Poner la aplicación a funcionar en un grupo de prueba y revisar si las personas realmente cambiaron sus rutas o si ahora entienden mejor el daño de la contaminación en el municipio.

## ACTORES, REQUERIMIENTOS FUNCIONALES Y NO F, HISTORIA DE USUARIOSActores claveConductores de vehículos particulares: Son usuarios que emplean carros o motos para movilizarse. Usarán la app para planear rutas menos contaminantes.Ciclistas: Personas que usan la bicicleta. Interactuarán con el sistema buscando rutas seguras con ciclovías y baja contaminación.Peatones y usuarios a pie: Habitantes que caminan distancias cortas. Recibirán alertas ambientales y consejos sobre calidad del aire.Usuarios del transporte público: Pasajeros de bus o metro interesados en optimizar sus traslados en función de salud ambiental.Ciudadanos y residentes de Itagüí: Público general afectado por la contaminación (niños, ancianos, etc.), que se benefician de recomendaciones y educación ambiental de la app.Secretaría de Movilidad de Itagüí: Entidad gubernamental interesada en mejorar la movilidad urbana sostenible; servirá de stakeholder organizacional.Área Metropolitana del Valle de Aburrá (AMVA): Provee datos de calidad del aire. Colabora con el sistema mediante APIs externas de monitoreo ambiental.APIs de mapas y geolocalización: Servicios externos (por ejemplo Google Maps, OpenStreetMap) que ofrecen información geográfica y cálculo de rutas.Sensores y redes de calidad del aire: Sistemas externos que proporcionan mediciones de PM2.5 y CO₂ en tiempo real. La app consume estos datos para generar alertas.Desarrolladores/administradores del sistema: Equipo técnico responsable del mantenimiento de la aplicación. Monitorean su desempeño y actualizan contenido educativo.Requerimientos FuncionalesRegistro y perfil de usuario: La aplicación debe permitir a los usuarios registrarse y crear un perfil personalizado. Esto incluye ingreso de datos básicos (correo, nombre, etc.) para guardar preferencias y puntos acumulados.Cálculo de rutas eco-amigables: Debe calcular rutas basándose en el origen y destino ingresados, seleccionando las con menor huella de carbono posible. La app debe estimar y mostrar al usuario la huella de carbono de cada ruta propuesta.Selección de modo de transporte: El sistema debe permitir que el usuario indique su medio (auto, bicicleta, a pie). Según esto, la ruta sugerida priorizará carriles bici o caminos peatonales cuando corresponda.Alertas de calidad del aire: Debe notificar al usuario cuando en su ubicación haya mala calidad del aire. Al superar ciertos umbrales ambientales, la app envía alertas con recomendaciones (por ejemplo, evitar salir).Gamificación y recompensas: La aplicación debe asignar puntos o recompensas cuando el usuario elija rutas con menor contaminación. Cada vez que complete un viaje por una ruta ecológica, el sistema suma puntos a su perfil.Contenido educativo: Debe ofrecer lecturas sencillas sobre movilidad sostenible, huella de carbono, PM2.5, ralentí, etc. Esta información se accede desde la app para que el usuario aprenda cómo cuidar su salud y el medio ambiente.Requerimientos No FuncionalesDe acuerdo con estándares de calidad (por ejemplo ISO/IEC 25010), los requisitos no funcionales se clasifican típicamente en producto, organizacionales y externos. Ejemplos para cada categoría en EcoRuta Itagüí son:Producto: Debe ser eficiente, rápido y fácil de usar. Por ejemplo, el cálculo de rutas no debe tardar más de unos segundos y la interfaz debe ser intuitiva para usuarios de diferentes edades. El sistema debe ser confiable (disponibilidad casi continua) y funcionar correctamente en dispositivos móviles comunes.Organizacionales: La implementación seguirá metodologías ágiles (Scrum) según las prácticas del equipo. Se adoptarán estándares internos de la institución educativa (p.ej. códigos limpios, repositorios compartidos) para facilitar el mantenimiento. También se considerará la escalabilidad interna del sistema para futuras mejoras.Externos: La aplicación debe cumplir la legislación colombiana vigente, por ejemplo protegiendo los datos personales de acuerdo con la Ley 1581 de 2012 (Habeas Data). Asimismo respetará normativas ambientales locales (difundiendo información oficial del AMVA). Se integrará únicamente con fuentes de datos autorizadas (APIs de mapas y calidad del aire) para garantizar la legalidad y veracidad de la información.Historias de Usuario (Enfoque Ágil)La redacción de historias de usuario sigue el patrón: “Como \[rol\] quiero \[funcionalidad\] para \[beneficio\]”. Cada historia incluye criterios de aceptación en formato condicional (“Si …, Cuando …, Entonces …”). Ejemplos clave:Como conductor de vehículo particular, quiero que la aplicación sugiera la ruta más ecológica entre mi origen y destino para reducir mi huella de carbono personal.Criterio de Aceptación 1: Si el usuario ingresa un origen y destino válidos, cuando solicita la ruta ecológica, entonces la aplicación muestra la ruta con menor huella de carbono.Criterio de Aceptación 2: Si el usuario completa el viaje por la ruta sugerida, entonces el sistema actualiza sus puntos acumulados por viaje limpio.Como ciclista, quiero encontrar rutas que prioricen ciclovías y baja contaminación, para desplazarme protegiendo mi salud.Criterio 1: Si el usuario selecciona “bicicleta” como modo de transporte, cuando calcula la ruta, entonces la aplicación ofrece trayectos con carril bici y muestra el nivel de contaminación asociado.Criterio 2: Si la ruta recomendada tiene baja contaminación, entonces la aplicación otorga puntos adicionales a favor del usuario (reforzando el hábito saludable).Como peatón habitual, quiero recibir alertas de alta contaminación en mi zona para evitar salir cuando el aire sea insalubre.Criterio 1: Si el nivel de PM2.5 supera el umbral establecido en la ubicación del usuario, entonces la app envía una notificación de alerta sobre mala calidad del aire.Criterio 2: Si el usuario abre la notificación de alerta, entonces la aplicación muestra recomendaciones (por ejemplo, “Evite ejercicio al aire libre”) y la duración estimada de la alerta.Como usuario registrado de EcoRuta, quiero acumular puntos cada vez que elija rutas con menor contaminación, para motivarme a adoptar hábitos sostenibles.Criterio 1: Si el usuario completa un viaje con la ruta de menor huella de carbono, entonces el sistema agrega los puntos correspondientes a su perfil.Criterio 2: Si el usuario consulta su perfil o historial, entonces puede ver el total de puntos acumulados y los logros obtenidos hasta el momento.Como ciudadano de Itagüí interesado en el medio ambiente, quiero acceder a contenido educativo sencillo sobre movilidad sostenible y calidad del aire, para aprender a proteger mi salud y el entorno.Criterio 1: Si el usuario ingresa al módulo educativo de la aplicación, cuando selecciona un tema (p.ej. “Huella de carbono”), entonces se despliega la información explicativa correspondiente de forma clara.Criterio 2: Si el usuario lee un artículo completo o responde un breve cuestionario de aprendizaje, entonces la aplicación marca esa sección como completada (por ejemplo con un ícono de verificación).Cada historia y criterio propuesto está directamente vinculado a la solución del problema descrito (movilidad sostenible en Itagüí) y se centra en qué debe hacer el sistema sin detallar cómo implementarlo.Fuentes: Se han utilizado fuentes especializadas en metodologías ágiles y movilidad sostenible para guiar la especificación. Por ejemplo, los requisitos funcionales se expresan siguiendo la forma “La aplicación debe …” y la literatura sugiere que una aplicación de movilidad sostenible debe evaluar la huella de carbono de las rutas. Los requisitos no funcionales se clasifican en producto, organizacionales y externos, asegurando cobertura de rendimiento, usabilidad, seguridad y cumplimiento legal. Los formatos de historias de usuario y criterios de aceptación se basan en la práctica ágil estándar.
# Actividad - Ingeniería de Requisitos

## 1\. Historia de Usuario (HU)

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | HU-01 |
| Título | Consulta de rutas de transporte público |
| Como | Usuario del transporte público |
| Quiero | Consultar rutas y horarios disponibles |
| Para | Planificar mis desplazamientos y llegar a tiempo a mi destino |

## 2\. Requisito Funcional (RF)

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RF-01 |
| HU Relacionada | HU-01 |
| Descripción | El sistema debe mostrar las rutas, paradas y horarios disponibles de manera clara y actualizada. |

## 3\. Requisito No Funcional (RNF)

|     |     |
| --- | --- |
| Campo | Descripción |
| ID  | RNF-01 |
| Categoría | Rendimiento |
| Descripción | El sistema debe cargar la información de rutas de forma rápida. |
| Métrica | La información debe mostrarse en menos de 3 segundos. |
REFERENCIAS

- - Área Metropolitana del Valle de Aburrá \[AMVA\]. (2023). _Informe de gestión ambiental y estado de la calidad del aire en el territorio metropolitano_. Publicaciones AMVA. [https://www.metropol.gov.co](https://www.metropol.gov.co/)
    - Bedoya, J. F., & Martínez, E. (2022). Impacto del ralentí vehicular en las emisiones de dióxido de carbono en zonas de alta congestión vial urbana. _Revista Politécnica Colombiana_, 18(35), 45-58. [https://revistas.elpoli.edu.co](https://revistas.elpoli.edu.co/)
    - Gaviria, C. A., Benito, G., & Agudelo, R. M. (2021). Contaminación por material particulado (PM2.5) y su relación con enfermedades respiratorias en el sur del Valle de Aburrá. _Revista de Salud Pública de Antioquia_, 27(2), 112-125. [https://www.udea.edu.co](https://www.udea.edu.co/)
    - Organización de las Naciones Unidas \[ONU\]. (2021). _La movilidad sostenible y los Objetivos de Desarrollo Sostenible: Un camino hacia la acción climática_. Informes Temáticos de la ONU. https://www.un.org/sustainabledevelopment/es/
    - Anuario Estadístico Itagüí, donde se observan los datos de vehículos: https://itagui.gov.co/anuarioitagui/
    - Población de Itagü: https://telencuestas.com/censos-de-poblacion/colombia/2026/antioquia/itagui
    - Cantidad de vehículos en itagui:https://www.itagui.gov.co/sitio/ver_noticia/En-Itag-registran-una-reduccin-del-65--en-las-muertes-por-accidentes-de-trnsito?utm_source=chatgpt.com
