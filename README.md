# Security Frameworks

Bienvenidos a la guía básica de Marcos de seguridad

Esta guía esta realizada gracias a los conceptos adquiridos mediante el programa de Google de Ciberseguridad:

https://www.coursera.org/professional-certificates/google-cybersecurity

## Security Frameworks and controls

Estos marcos son directrices utilizadas para crear planes para mitigar los riesgos y las amenazas a los datos y la privacidad.

**Tipos de marcos de seguridad**:

- **Seguridad física:** Buscan mantener la seguridad en el entorno de trabajo (por ejemplo, acceso con tarjeta de identificación).

- **Prevención, detección y respuesta a las brechas de seguridad:** Busca proteger contra ataques de ingeniería social como el phishing.

- **Concienciación y educación de los empleados:** Aumentar la concienciación de los empleados y educarlos sobre cómo pueden proteger la organización. Es importante mantener a los empleados de una empresa formados. 

  EJEMPLOS:

  - **Marco de Amenazas Cibernéticas (CTF o Cyber Threat Framework):** Proporciona un lenguaje común para describir y comunicar amenazas cibernéticas, mejorando la eficiencia de la respuesta.
  - **Organización Internacional de Normalización/Comisión Electrotécnica Internacional (ISO/IEC o International Organization for Standardization/International Electrotechnical Commission ) 27001:** Un marco reconocido internacionalmente que describe los requisitos para un sistema de gestión de seguridad de la información, mejores 

**Controles de seguridad:** Se utilizan junto con los marcos para alcanzar los objetivos de seguridad de una organización.

- **El cifrado**: convertir datos de un formato legible a un formato codificado, generalmente de texto plano a texto cifrado. Esto asegura la confidencialidad de los datos sensibles.

- **La autenticación**: verifica la identidad de un usuario o dispositivo. Los métodos más avanzados como la autenticación multifactor (MFA) requieren verificación adicional, como un código de seguridad o biometría.

- **La autorización**: determina si un usuario tiene permiso para acceder a recursos específicos dentro de un sistema.

  Ejemplos :

  - **Físicos:** Puertas, vallas, guardias de seguridad, CCTV, tarjetas de acceso.
  - **Técnicos:** Firewalls, MFA, software antivirus.
  - **Administrativos:** Separación de funciones, autorización, clasificación de activos.

### CIA

La tríada CIA (confidencialidad, integridad y disponibilidad) es fundamental para establecer la postura de seguridad de una organización.

**Confidencialidad:** Solo los usuarios autorizados pueden acceder a determinados activos o datos. En una organización, la confidencialidad se puede mejorar mediante la implementación de principios de diseño, como el principio del mínimo privilegio. Este principio limita el acceso de los usuarios a la información que necesitan para completar sus tareas laborales.

**Integridad:** Los datos son verificablemente correctos, auténticos y fiables. Es esencial contar con protocolos para verificar la autenticidad de los datos. Una forma de verificar la integridad de los datos es mediante la criptografía, que se utiliza para transformar los datos de forma que las partes no autorizadas no puedan leerlos ni manipularlos. 

**Disponibilidad:** Los datos son accesibles para quienes están autorizados a utilizarlos. Cuando un sistema se adhiere a los principios de disponibilidad y confidencialidad, los datos pueden utilizarse cuando se necesitan. 

### NIST FRAMEWORKS:

- **Marco de Ciberseguridad NIST (CSF):** Un marco de trabajo voluntario que consiste en estándares, directrices y mejores prácticas para gestionar el riesgo de ciberseguridad. Incluye cinco funciones principales: identificar, proteger, detectar, responder y recuperar.

  <img align="center" src="/img/2ºimagenn.PNG"  />

  - **Identificar:** Comprender y gestionar los riesgos de ciberseguridad y su impacto en los activos y las personas de una organización.
  - **Proteger:** Implementación de políticas, procedimientos, formación y herramientas para mitigar las amenazas de ciberseguridad.
  - **Detectar:** identificación de posibles incidentes de seguridad y la mejora de las capacidades de supervisión para una detección más rápida y eficiente.
  - **Responder:** Procedimientos adecuados para contener, neutralizar y analizar los incidentes de seguridad, y para aplicar mejoras al proceso de seguridad.
  - **Recuperar:** Restauración de los sistemas afectados al funcionamiento normal después de un incidente.

- **Publicación Especial NIST (SP) 800-53:** Proporciona un marco de trabajo unificado para proteger la seguridad de los sistemas de información dentro del gobierno federal de los Estados Unidos. Utiliza controles de seguridad para mantener la tríada CIA (Confidencialidad, Integridad y Disponibilidad) para los sistemas gubernamentales.

### OWASP o **Open Web Application Security Project**

Es una organización sin ánimo de lucro que se centra en mejorar la seguridad de las aplicaciones web.

<img align="center" src="/img/1ºimagenn.PNG"  />



Sus principios son:

- **Minimizar la superficie de ataque:** Reducir el número de vulnerabilidades potenciales que los atacantes pueden explotar.
- **Mínimo privilegio:** Acceso mínimo necesario para realizar las tareas por parte de los trabajadores.
- **Defensa en profundidad:** Implementar múltiples capas de controles de seguridad para protegerse contra las amenazas.
- **Separación de funciones:** Evitar que las personas tengan demasiado poder y cometan fraude.
- **Mantener la seguridad simple:** Evitar controles de seguridad demasiado complejos que sean difíciles de gestionar.
- **Solucionar los problemas de seguridad correctamente:** Identificar y abordar las vulnerabilidades de forma rápida y eficaz.

### Security Audits o Auditorias de seguridad

Son revisiones independientes que evalúan si una organización está cumpliendo con los criterios internos y externos de seguridad. Existen dos tipos las internas y las externas

- El objetivo de una auditoría es asegurar que las prácticas de TI de una organización están cumpliendo con los estándares de la industria y de la organización, tambien se basa en identificar y abordar las áreas de remediación y crecimiento.

Marcos de trabajo como NIST CSF e ISO 27000 pueden ayudar a las organizaciones a prepararse para las auditorías de seguridad de cumplimiento normativo.

Hay tres categorías principales de controles a revisar durante una auditoría: 

- Administrativos
- Tecnicos
- Fisicos.

**1. Controles Administrativos/Gerenciales:**

- Se enfocan en el factor humano de la ciberseguridad.
- Incluyen políticas y procedimientos que definen cómo una organización administra los datos y las responsabilidades de los empleados.
- La aplicación de estas políticas puede requerir controles técnicos o físicos.

**2. Controles Técnicos:**

- Consisten en soluciones como firewalls, IDS, IPS, productos antivirus y encriptación.
- Se utilizan para cumplir los objetivos de la organización.

**3. Controles Físicos:**

- Incluyen cerraduras de puertas, cerraduras de gabinetes, cámaras de vigilancia y lectores de tarjetas.
- Limitan el acceso físico a los activos por parte de personal no autorizado.

**Tipos de Controles:**

- **Preventivos:** diseñados para evitar que ocurra un incidente.
- **Correctivos:** utilizados para restaurar un activo después de un incidente.
- **Detectivos:** implementados para determinar si un incidente ha ocurrido o está en progreso.
- **Disuasivos:** diseñados para desalentar los ataques.

**Ejemplos de Controles:**

- **Administrativos:** Privilegios mínimos, planes de recuperación de desastres, políticas de contraseñas, políticas de control de acceso, políticas de administración de cuentas, separación de funciones.
- **Técnicos:** Firewall, IDS/IPS, encriptación, copias de seguridad, administración de contraseñas, software antivirus, monitoreo manual, mantenimiento e intervención.
- **Físicos:** Caja fuerte con control de tiempo, iluminación adecuada, circuito cerrado de televisión (CCTV), gabinetes con cerradura, señalización que indica el proveedor del servicio de alarma, cerraduras, detección y prevención de incendios.

Una lista de verificación de la auditoría debe incluir el alcance de la auditoría, una evaluación de riesgos, la auditoría en sí, un plan de mitigación y la comunicación de los resultados a las partes interesadas.



A continuación vamos a realizar una simulación de auditoria en base a unos datos proporcionados por el curso de google
