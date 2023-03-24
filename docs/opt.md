Optimización

1. ¿Qué se entiende por hediondez del código? Pon al menos 5 ejemplos.

   La hediondez del código, también conocida como "code smell" en inglés, se refiere a un conjunto de características del código fuente que pueden indicar la presencia de problemas en el diseño o la implementación del software. Estas características no son necesariamente errores de programación, pero pueden dificultar la comprensión, el mantenimiento o la escalabilidad del código. Aquí hay algunos ejemplos comunes de hediondez del código:

   1. Código duplicado: cuando se repiten bloques de código similares en varias partes del programa, lo que dificulta la corrección y la actualización del software.
   2. Clases o métodos demasiado grandes: cuando las clases o los métodos son demasiado extensos y hacen demasiado trabajo, lo que dificulta la comprensión y el mantenimiento del código.
   3. Nombres de variables o funciones confusos: cuando los nombres de las variables o las funciones no son claros o descriptivos, lo que dificulta la comprensión del código.
   4. Dependencias circulares: cuando dos o más clases se llaman entre sí en un ciclo, lo que dificulta la comprensión y el mantenimiento del software.
   5. Comentarios excesivos o inadecuados: cuando se usan demasiados comentarios en el código o cuando los comentarios no reflejan adecuadamente lo que está sucediendo en el código, lo que dificulta la comprensión del programa.

2. ¿Qué tipo de herramienta utilizamos para hacer análisis estático del código?

   Para hacer análisis estático del código se utilizan herramientas llamadas "análisis estático de código" o "static code analysis" en inglés. Estas herramientas examinan el código fuente de un programa sin ejecutarlo y buscan posibles errores, vulnerabilidades, redundancias, violaciones de estándares de codificación y otros problemas comunes.

   Existen diversas herramientas de análisis estático de código disponibles en el mercado, algunas de ellas son gratuitas y de código abierto, mientras que otras son comerciales. Algunas de las herramientas más populares son:

   1. SonarQube
   2. Checkstyle
   3. PMD
   4. ESLint
   5. Code Climate
   6. ReSharper
   7. Coverity
   8. Infer
   9. FindBugs
   10. Lint

3. ¿Qué sitios web nos permiten hacer análisis estático del código o **Continuous Inspection**?

   1. SonarCloud: Es una plataforma gratuita de análisis estático de código basada en la nube que admite varios lenguajes de programación, incluyendo Java, JavaScript, C#, C/C++, Python y más. Ofrece análisis continuo del código y proporciona informes detallados sobre la calidad del código, la seguridad y la cobertura de pruebas.
   2. CodeClimate: Ofrece análisis continuo del código para múltiples lenguajes de programación, incluyendo Ruby, Python, JavaScript, PHP, Java y TypeScript. Proporciona informes detallados sobre la calidad del código, la seguridad, la cobertura de pruebas y el rendimiento.
   3. Codacy: Es una plataforma de análisis estático de código que admite más de 30 lenguajes de programación. Proporciona análisis continuo del código, integración con sistemas de control de versiones y herramientas de colaboración.
   4. BetterCodeHub: Es una herramienta de análisis estático de código que se enfoca en la aplicación de los principios del "12 Factor App" para mejorar la calidad del código. Proporciona informes detallados sobre la calidad del código, la arquitectura, el diseño y las mejores prácticas.
   5. DeepCode: Es una herramienta de análisis estático de código basada en la inteligencia artificial que ofrece análisis continuo del código para múltiples lenguajes de programación. Proporciona informes detallados sobre la calidad del código, la seguridad y las mejores prácticas.

4. Instala en Netbeans el plugin **FindBugs**, si no lo tienes aún instalado.

   ![211801034-69db1e8e-1f1c-4fd0-b840-2e47e0bcf42d](/img/211801034-69db1e8e-1f1c-4fd0-b840-2e47e0bcf42d.png)

   ![211783961-839adcd3-49f6-4c8e-a965-1617ea01cedf](/img/211783961-839adcd3-49f6-4c8e-a965-1617ea01cedf.png)

5. Realiza **análisis estático de código** para las clases del proyecto *miapp*. Consulta el siguiente enlace:![211817037-645ac42d-a4b4-4be4-99a5-dbaec99ab0ca](/img/211817037-645ac42d-a4b4-4be4-99a5-dbaec99ab0ca.png)

6. Indica al menos un `code smell` relevante de cada clase. Explica cómo podría solucionarse.

   1. Análisis dinámico: unit tests
   2. Análisis estático: lint

7. ¿Qué es la refactorización?

   1. Es el proceso de reestructurar un código fuente, alterando su estructura interna sin cambiar su comportamiento externo.

8. ¿Qué técnicas se utilizan a menudo a la hora de refactorizar?

   1. Técnicas:
      - Renombrado de variables
      - Pasar código duplicado a funciones
      - Eliminación de código inalcanzable
      - Eliminación de código redundante
      - Eliminación de código muerto
