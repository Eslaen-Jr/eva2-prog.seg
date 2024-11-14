# OWASP y programación segura

## ¿Qué es OWASP y cuál es su principal objetivo?
*OWASP (Open Web Application Security Project) es una organización de nivel mundial sin fines de lucro dedicada a la mejora de seguridad de software. Su principal objetivo es darle visibilidad a la seguridad de software, para darle la posibilidad a las personas y organizaciones de tomar decisiones informadas.*

## ¿Qué es el OWASP Top 10 y por qué es importante para los desarrolladores?
*OWASP Top 10 es un proyecto de OWASP, en el que la organización ha plasmado en un documento lo que a su consideración, después de recopilar las vulnerabilidades de cientos de organizaciones y más de 100.000 aplicaciones y API's del mundo real, son los 10 riesgos más relevantes en aplicaciones. Se centra en educar y crear consciencia sobre las consecuencias de las deebilidades más comunes e importantes de la seguridad de las aplicaciones web y proporciona técnicas básicas para protegerse contra áreas con problemas de riesgo alto, y proporcionar orientación de cómo continuar desde allí.*

## Describe brevemente dos de las vulnerabilidades del OWASP Top 10 2017. 
**Vulnerabilidad A1: 2017 Inyección:**
*Las fallas de inyección, como SQL, NoSQL, OS o LDAP ocurren cuando se envían datos no confiables a un intérprete, como parte de un comando o consulta. Los datos dañinos del atacante pueden engañar al intérprete para que ejecute comandos involuntarios o acceda a los datos sin la debida autorización.*

**Vulnerabilidad A10: 2017 Registro y Monitoreo Insuficientes:**
*El registro y monitoreo insuficiente, junto a la falta de respuesta ante incidentes permiten a los atacantes mantener el ataque en el tiempo, pivotear a otros sistemas y manipular, extraer o destruir datos. Los estudios muestran que el tiempo de detección de una brecha de seguridad es mayor a 200 días, siendo típicamente detectado por terceros en lugar de por procesos internos.*

## ¿Qué es OWASP ASVS y cuáles son sus niveles de verificación? 
*AVS (Aplication Security Verification Standard), es un proyecto que alude al estándar de verificación de seguridad de aplicaciones de OWASP y proporciona una base para probar los controles técnicos de seguridad de las aplicaciones web.*

*Consta de 3 niveles de verificación de seguridad y a medida que pasa de nivel la profundidad incrementa:*
*AVS Nivel 1: Oportunista: Dirigido a todo tipo de software o aplicación*
*AVS Nivel 2: Estándar: Para aplicaciones que contienen datos sensibles, que requieren protección*
*AVS Nivel 3: Avanzado:  para las aplicaciones más críticas, aplicaciones que realizan transacciones de alto valor, que contienen datos médicos confidenciales, o cualquier aplicación que requiera el más alto nivel de confianza*

## ¿Cuál es la diferencia entre los niveles 1 y 3 de OWASP ASVS? 
**Casos de Utilidad:**
*El nivel 1 se utiliza en software que requiere escasa confienza en el uso correcto de los controles de seguridad.*
*El nivel 3 está reservado para aplicaciones que requieren niveles significativos de verificación de seguridad, como las que se ven en áreas militares, de salud, seguridad, infraestructura, etc. En otras palabras se requiere en aplicaciones que realizan funciones críticas en las que una falla de seguridad contituye un daño severo en las operaciones.*

**Manejo de Nivel:**
*El nivel 1 puede ser automatizado con herramientas o manejarlo manualmente sin acceso al código fuente*
*El nivel 3 requiere un análisis de mayor profundidad, arquitectura, codificación y Testing en todo nivel*

**Manejo de Amenazas:**
*En el nivel 1, las amenazas a la aplicación probablemente provendrán de atacantes que utilizan técnicas simples y de bajo esfuerzo para identificar vulnerabilidades fáciles de encontrar y de explotar*
*En el nivel 3, las amenazas serán mucho más severas por lo que el nivel incluye controles para asegurar la confidencialidad (cifrado, por ejemplo), integridad (transacciones, validación de la entrada), disponibilidad (manejo de carga), autenticación (incluyendo autenticación entre sistemas), no repudio, autorización y auditoría (bitácoras)*

## ¿Qué es el modelado de amenazas y cuáles son sus beneficios? 
*El modelado de amenazas es un elemento central del ciclo de vida de desarrollo de seguridad de Microsoft (SDL). Es una técnica de ingeniería que se puede utilizar para identificar amenazas, ataques, vulnerabilidades y contramedidas que podrían afectar una aplicación. Puede utilizar el modelado de amenazas para dar forma al diseño de una aplicación, cumplir los objetivos de seguridad de la empresa y reducir el riesgo.*
*Entre sus beneficios se encuentran: los profesionales de TI pueden indentificar posibles amenazas y vulnerabilidades de seguridad, Cuantificar la gravedad de cada una, Priorizar las técnicas para mitigar los ataques, proteger los recursos de TI.*

## Nombra dos metodologías de modelado de amenazas.
**STRIDE: (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, and Elevation of Privilege)**
*Ayuda a garantizar que los desarrolladores de software de Windows de Microsoft piensen en la seguridad durante la fase de diseño*

**TRIKE: (visual, ágil y de amenazas simples)**
*Es el modelado de amenazas centrado en la empresa. Se basa principalmente en escalar a las otras metodologías de modelado de amenazas*

## ¿Qué es el SDL y cómo ayuda a la seguridad del software?
*El ciclo de vida de desarrollo de seguridad (SDL) es un proceso de control de seguridad orientado al desarrollo de software. Ha desempeñado un papel muy importante en la integración de la seguridad y de la privacidad en el software y la cultura de Microsoft*
*Con un enfoque tanto holístico como práctico, SDL tiene como objetivo reducir el número y la gravedad de las vulnerabilidades en el software.Es una manera de evitar problemas de seguridad en el desarrollo, entre los cuales se encuentran: Anticipar Fallas en el Código, Remover código viejo, Eliminar funciones antiguas.*

