

Servicio de autenticación central (CAS)
Licencia Gorjeo Apoyo Gitter Flojo Desbordamiento de pila

Introducción
Bienvenido al hogar del proyecto del Servicio de autenticación central , más comúnmente conocido como CAS. CAS es una solución empresarial de inicio de sesión único multilingüe para la web e intenta ser una plataforma integral para sus necesidades de autenticación y autorización.

CAS es un protocolo de autenticación abierto y bien documentado. La implementación principal del protocolo es un componente de servidor Java de código abierto con el mismo nombre alojado aquí, con soporte para una gran cantidad de funciones y protocolos de autenticación adicionales.

Contribuciones
Guía contribuyente Solicitudes de extracción abiertas

Cómo contribuir
Si ya ha identificado una mejora o un error, se recomienda ENCARECIDAMENTE que simplemente envíe una solicitud de extracción para abordar el caso. No hay necesidad de una ceremonia especial para crear temas separados. La solicitud de extracción ES el problema y se rastreará y etiquetará como tal.

Documentación Javadoc
Versión	Referencia
	Enlace
	Enlace
	Enlace
Los recursos adicionales están disponibles de la siguiente manera:

Blog de Apereo
Notas de lanzamiento
Apoyo
Política de mantenimiento
Programa de lanzamiento
Despliegue
Guía contribuyente Solicitudes de extracción abiertas codecov Estado de construcción Estado de construcción Maven Central Lanzamientos de Github

Se recomienda implementar CAS localmente mediante el método WAR Overlay . SOLO se requiere clonar o descargar la base de código CAS si desea contribuir al desarrollo del proyecto.

Características
Las siguientes características son compatibles con el proyecto CAS:

Protocolo CAS v1, v2 y v3
Protocolo SAML v1 y v2
Protocolo OAuth v2
Protocolo de conexión OpenID y OpenID
Protocolo de solicitud pasiva de WS-Federation
Autenticación a través de JAAS, LDAP, RDBMS, X.509, Radius, SPNEGO, JWT, Remote, Apache Cassandra, Trusted, BASIC, Apache Shiro, MongoDb, Pac4J y más.
Autenticación delegada a WS-FED, Facebook, Twitter, SAML IdP, OpenID, OpenID Connect, CAS y más.
Autorización a través de ABAC, hora / fecha, REST, Grouper de Internet2 y más.
Implementaciones agrupadas de alta disponibilidad a través de Hazelcast, Ehcache, JPA, Apache Cassandra, Memcached, Apache Ignite, MongoDb, Redis, DynamoDb, Couchbase y más.
Registro de aplicaciones respaldado por JSON, LDAP, YAML, Apache Cassandra, JPA, Couchbase, MongoDb, DynamoDb, Redis y más.
Autenticación multifactor a través de Duo Security, YubiKey, RSA, Google Authenticator y más.
Interfaces de usuario administrativas para administrar el registro, el monitoreo, las estadísticas, la configuración, el registro de clientes y más.
Tema y marca de la interfaz de usuario global y por aplicación.
Gestión de contraseñas y aplicación de políticas de contraseñas.
Los cimientos de CAS se basan en: Spring Boot y Spring Cloud .

Desarrollo
Insignia de Codacy Asistente CLA Estado de dependencia Calidad Sonarqube Calidad Sonarqube

Para construir el proyecto localmente, siga esta guía . El calendario de lanzamientos está disponible aquí .

Apoyo
CAS es un software de código abierto 100% gratuito administrado por Apereo , con licencia de Apache v2 . Nuestra comunidad tiene acceso a todas las versiones del software CAS sin ningún costo. Damos la bienvenida a las contribuciones de nuestra comunidad de todos los tipos y tamaños. El tiempo y el esfuerzo para desarrollar y mantener este proyecto son dedicados por un grupo de voluntarios y contribuyentes . Las opciones de soporte se pueden encontrar aquí . Si usted (o su empleador) se beneficia de este proyecto, considere convertirse en Amigo de Apereo y contribuir.
