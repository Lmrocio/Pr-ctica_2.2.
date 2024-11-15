# Práctica_2.2.

> Integrantes del grupo: Rocío Luque, Antonio Caro, Adrián Diaz y Juan Herrador.

***Preguntas evaluativas:***

1. ¿Qué características comunes comparten los IDEs en términos de edición de código, depuración y control de versiones?

   - Edición de código. Entre las características cómunes concernientes con la edición y creación de código encontramos: soporte para varios lenguajes de programación (aunque sea limitado como en el caso de PyCharm), soporte para extensiones que nos pueden aportar herramientas para la edición, limitada refactorización del código (siendo el único punto negativo encontrado), autocompletado de código, pruebas automáticas realizadas al código (en su mayoría, con amplias prestaciones) y herramientas de análisis de código, mínimo, en un estado limitado.
     
   - Depuración. Encontramos, mínimo, un depurador básico que cumple su funcionalidad en todos los entornos observados. No obstante, en la mayoría de los casos tenemos un depurador complejo, con funciones más avanzadas que nos permiten realizar una depuración más sofisticada y precisa.
     
   - Control de versiones. En todos los IDEs comparados podemos encontrar un sistema de control de versiones integrado, especialmente destaca la compatibilidad con Git.
     
2. ¿Qué diferencias notaron en la forma en que los IDEs manejan módulos, personalización y generación de ejecutables?

   **Manejo de módulos/extensiones:**
   - VSCode tiene una gran cantidad de extensiones que permiten a los desarrolladores personalizarlo para casi cualquier lenguaje.
   - Visual Studio también ofrece un amplio soporte para módulos, especialmente para entornos de .NET y aplicaciones de Windows.
   - Fleet es adaptable y permite habilitar o deshabilitar funcionalidades específicas, siendo útil para varios lenguajes, aunque es más limitado comparado con VSCode.
   - NetBeans y PyCharm tienen menos extensiones en comparación y su soporte para módulos está enfocado en lenguajes específicos (Java en NetBeans y Python en PyCharm).

   **Personalización el entorno:**
   - VSCode es muy personalizable, desde temas hasta atajos y extensiones específicas.
   - Fleet permite personalización en temas y configuración básica, pero tiene menos opciones en comparación con VSCode.
   - PyCharm y NetBeans ofrecen menos opciones de personalización, ya que su entorno está más especializado y enfocado en sus lenguajes principales.
   - Visual Studio permite una personalización importante, especialmente para proyectos de .NET.

   **Generación de ejecutables:**
   - Visual Studio ofrece soporte nativo para compilar y generar ejecutables (.NET y C++).
   - NetBeans permite generar ejecutables para Java, mientras que PyCharm y VSCode requieren configuraciones adicionales para crear ejecutables en Python u otros lenguajes.
   - Fleet ofrece generación de ejecutables de forma limitada y necesita de herramientas externas o configuraciones adicionales para crear ejecutables en distintos lenguajes.

3. ¿Cuál de los IDEs elegidos consideran que es más adecuado para proyectos de desarrollo específicos y por qué?

   - VSCode: Ya que te instalas en plugin del lenguaje especifico que necesites, ademas de terner algunas caracteristicas mejor que los otros como por ejemplo la velocidad de carga, su amplio catalogo de extensiones, su alta personalizacion y su amplio soporte para realizar pruebas automatizadas haciendo que VSCode sea una de las mejores opciones disponibles, en caso de que el proyecto sea especificamente de Python si que en este caso seria mejor usar PyCharm debido a que se centra mas en este lenguaje.
   
4. ¿Qué IDE recomendarían a un equipo de desarrollo que trabaja en proyectos de Python, Java o Kotlin y por qué?
   - Recomendaría IntelliJ IDEA, es el IDE más completo para un equipo que trabaja con Python, Java y Kotlin, ya que ofrece soporte nativo para Java y Kotlin y es muy potente en cuanto a refactorización, depuración, y autocompletado.


***Evidencias:*** 

| Características |  VSCode   |  PyCharm  |  NetBeans |  Visual Studio |   Fleet  |
| --------------- | --------- | --------- | --------- | -------------- | -------- |
| Lenguajes soportados |Amplia variedad de lenguajes, dependiendo del plugin|Python, aunque soporta complementos para otros lenguajes|Java,php,Javascript, html, css, python,kotlin| C#, C++, Python, JavaScript, Visual Basic etc. | Python, C, C++, HTML, CSS, Java, Javascript, Kotlin, JSON, C#, Docker, Gradle|
| Velocidad de carga | Muy Rápida| Arranque más lento | No muy rápido | Rápida|Rápida|
| Soporte para extensiones | Muy amplio |Soporta extensiones, aunque está centrado en Python|Gran soporte de extensiones | Muy amplia |Solo tiene las extensiones para programar los diferentes lenguajes|
| Depurador |Básico pero funcional, puede mejorar con extensiones|Depurador para Python muy completo|muy avanzado|Complejo para múltiples lenguajes|Básico|
| Refactorización | Sí, limitada con extensiones|Muy avanzada|Es más limitada|Limitada, mediana cobertura|Si, pero limitado|
|Autocompletado de código | Sí, con extensiones|Sí, muy preciso| Sí|Avanzado, nativo| Sí |
| Control de versiones |Integrado, depende del plugin|Integrado (Git, Mercurial y Subversion)| Integrado |Integrado (Git y más)| Git  |
| Automatización de tareas |Sí, con extensiones (Task Runner, npm scripts)|Ofrece soporte para Makefile, Docker, etc.| Sí  |   Sí   |   Sí  |
| Soporte para múltiples lenguajes | Soporte para muchos lenguajes, con extensiones |Sí, aunque está centrado en Python | Sí  | Sí, múltiples lenguajes  |  Sí   |
|Personalización del entorno| Muy alto(temas extensiones, atajos) |Sí, centrado en las configuraciones de Python| Sí | Sí | Limitada |
|Integración con bases de datos | Limitada, depende del plugin | Buena integración | si tiene y tiene herramientas muy útiles |Soporte con varias bases de datos| Si, a través de un plugin|
| Pruebas automatizadas | Amplio soporte | Soporte para Pytest, Unittest, etc. | pruebas automatizadas amplia | Amplio soporte | Amplio soporte |
| Soporte para frameworks | Sí, mediante extensiones |Sí, especial para Django y Flask|Es bastante amplio| Amplio (ASP.NET, Entity Framework) |Si, limitado y a través de plugins|
| Configuración de entornos virtuales |Sí, mediante extensiones| Sí, para Python | Poco limitado | Configuración avanzada|Si, configuración avanzada|
| Herramientas de análisis de código |Limitado, depende de extensiones| Avanzado para Python| Varias herramientas y análisis de código  |Herramientas avanzadas|Limitado|
|Soporte para compilación/maven/gradle |Limitado, depende de extensiones|Limitado|Buen soporte|Nativo para múltiples lenguajes |  Sí  |
| Precio/licencia | Gratuito, código abierto | Pago (versión Community Edition es gratuita) | Código abierto y gratuito |Pago (Versión Community gratuita)|En desarrollo, Pagó por definir (Gratuito para educación y hobbies)|

