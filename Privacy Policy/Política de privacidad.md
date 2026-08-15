# Política de Privacidad

**Fecha de Vigencia:** 07.08.2026  
**Responsable del Tratamiento:** Tomasz Rutkowski, persona física con residencia en Polonia, desarrollador independiente de la aplicación "Chess M8".  
**Nombre de la Aplicación:** ChessM8

---

## 1. Introducción
Respetamos su privacidad. Esta Política de Privacidad explica cómo ChessM8 (la "Aplicación") recopila, utiliza y protege la información. Al utilizar la Aplicación, usted acepta los términos de esta política.

---

## 2. Recopilación y Procesamiento de Datos (Arquitectura Local-First)
La Aplicación está diseñada con un enfoque "Local-First". Esto significa que priorizamos su privacidad manteniendo sus datos en su dispositivo.

### A. Datos Personales
La Aplicación obtiene datos públicos de partidas de ajedrez (archivos PGN) de servicios de terceros, que pueden incluir:
* Nombres de usuario (por ejemplo, Lichess.org o Chess.com).
* Movimientos de la partida, marcas de tiempo y valoraciones.

No almacenamos datos personales en nuestros propios servidores; los datos se transmiten directamente desde su dispositivo a las API de terceros a su solicitud.

### B. Datos Técnicos
* **Dirección IP:** Cuando la Aplicación se conecta a las API de terceros, su dirección IP es visible para esos proveedores (Chess.com/Lichess), pero no nos es enviada ni almacenada por nosotros.

### C. Permisos del Dispositivo
Para funcionar, la Aplicación requiere:
* **Acceso a Internet:** Para conectarse específicamente a las API de Chess.com y Lichess.org.
* **Almacenamiento (Lectura/Escritura):** Para guardar y recuperar archivos PGN en su dispositivo (cuando corresponda).

---

## 3. Finalidades y Base Legal para el Procesamiento

### A. Usuarios del Área Económica Europea (AEE) (GDPR)
Si se encuentra en el AEE, procesamos datos personales para las siguientes finalidades:
1. **Prestación del servicio y análisis de partidas:** Permitirle descargar sus partidas, analizarlas y mostrar estadísticas dentro de la Aplicación.  
   *Base legal:* Artículo 6(1)(b) del GDPR (cumplimiento de un contrato para proporcionar funciones solicitadas).
2. **Garantizar la funcionalidad técnica:** Uso de acceso a internet para comunicarse con los servidores de Chess.com y Lichess.org de forma segura y fiable.  
   *Base legal:* Artículo 6(1)(f) del GDPR (interés legítimo en garantizar funcionalidad y seguridad adecuadas).
3. **Almacenamiento local para uso sin conexión:** Guardar archivos PGN en su dispositivo para acceso sin conexión activa.  
   *Base legal:* Artículo 6(1)(b) del GDPR.

---

## 4. Servicios de Terceros
La Aplicación actúa como una interfaz cliente. Cuando utiliza la función "Importar", su dispositivo se conecta directamente a:
* **Chess.com** (sujeto a su Política de Privacidad)
* **Lichess.org** (sujeto a su Política de Privacidad)

No actuamos como intermediarios. Sus cabeceras de solicitud (incluido el User-Agent de la Aplicación) son visibles para estos servicios durante la conexión.

---

## 5. Divulgaciones Regionales de Privacidad y Derechos de los Usuarios

Como no almacenamos sus datos en servidores externos, usted mantiene el control directo sobre su información, independientemente de su residencia.

### 5.1. Área Económica Europea (AEE) y Reino Unido (RU)
Bajo el GDPR y el UK GDPR, usted tiene los siguientes derechos:
* **Acceso y Portabilidad:** Todos los datos se almacenan directamente en su dispositivo.
* **Eliminación:** Puede eliminar todos los datos en cualquier momento limpiando la caché/datos de la Aplicación en la configuración del dispositivo o desinstalando la Aplicación.
* **Derecho a Oponerse/Restringir:** Puede detener el procesamiento en cualquier momento dejando de usar la Aplicación o desactivando las funciones de importación.

### 5.2. California / Estados Unidos (CCPA / CPRA)
* **Sin Venta o Compartición de Información Personal:** No vendemos ni compartimos información personal, y no lo hemos hecho en los 12 meses anteriores.
* **Información Sensible:** No recopilamos ni procesamos información personal sensible que requiera controles de exclusión.
* **Ejercicio de Derechos:** Los residentes de California pueden ejercer sus derechos administrando el almacenamiento local del dispositivo o contactándonos.

### 5.3. Brasil (LGPD)
Bajo la Lei Geral de Proteção de Dados (LGPD):
* **Bases Legales:** El procesamiento para análisis de partidas y almacenamiento local se realiza en virtud del Artículo 7(V) de la LGPD (ejecución de contrato). Las conexiones técnicas a API externas se realizan con base en el Artículo 7(IX).
* **Derechos:** Puede ejercer sus derechos de confirmación, acceso o eliminación administrando el almacenamiento local en su dispositivo.

### 5.4. India (DPDP Act 2023)
Bajo la Digital Personal Data Protection Act 2023:
* **Derechos del Titular de los Datos:** Tiene derecho a solicitar la eliminación y retirar el consentimiento para el procesamiento.
* **Ejecución:** Dado que todos los datos residen localmente en su dispositivo, puede ejercer estos derechos limpiando los datos de la Aplicación o desinstalándola.

### 5.5. Otras Jurisdicciones
Si reside en otra jurisdicción (como Canadá, Australia, Suiza, Japón o Singapur), conserva plenos derechos para acceder y eliminar sus datos locales directamente en su dispositivo.

---

## 6. Transferencias Internacionales de Datos
Cuando usa las funciones de importación, su dispositivo se conecta directamente a servidores de terceros:
* **Chess.com:** Los servidores pueden estar ubicados en los Estados Unidos. La conexión con Chess.com hace que su dispositivo envíe solicitudes de red estándar (incluida su dirección IP y el nombre de usuario solicitado) directamente a esos servidores.
* **Lichess.org:** Infraestructura con sede en la Unión Europea (Francia/Alemania).

Si accede a la Aplicación desde fuera de los Estados Unidos o la Unión Europea, iniciar una importación resultará en la transmisión directa de los datos de conexión a esos servidores de terceros a través de fronteras internacionales.

---

## 7. Analítica, Perfilado y SDKs de Terceros
* **Sin SDKs de Seguimiento:** La Aplicación no utiliza SDKs de análisis, publicidad o informes de fallos (como Google Analytics, Firebase o AdMob).
* **Sin Perfilado ni Decisiones Automatizadas:** No realizamos perfilado, evaluación ni decisiones automatizadas basadas en sus datos personales o historial de juego.
* **Sin Telemetría:** Ningún dato sobre su interacción con la Aplicación se transmite a nosotros.

---

## 8. Seguridad de los Datos
Como los datos se almacenan localmente, la seguridad de sus datos depende de la seguridad de su dispositivo. Recomendamos:
* Usar código de acceso del dispositivo o bloqueo biométrico.
* Mantener el sistema operativo actualizado.
* Evitar el uso de la Aplicación en dispositivos comprometidos ("rooted" o "jailbroken").

---

## 9. Privacidad de los Niños
La Aplicación no está dirigida a niños menores de 16 años (o la edad mínima requerida por la ley local, si es menor — pero no por debajo de 13).

No permitimos conscientemente que niños por debajo de esta edad utilicen las funciones de importación. El uso de servicios de terceros (Chess.com y Lichess.org) a través de la Aplicación sigue sujeto a las políticas de edad de esos servicios.

---

## 10. Ley Aplicable y Resolución de Disputas
Esta Política de Privacidad y cualquier disputa que surja de la misma se regirán e interpretarán de acuerdo con las leyes de Polonia, sin tener en cuenta sus disposiciones sobre conflicto de leyes.

---

## 11. Derecho a Presentar una Queja (Usuarios del AEE)
Si se encuentra en el AEE y cree que sus derechos de privacidad han sido vulnerados, puede presentar una queja ante su autoridad local de protección de datos o ante nuestro supervisor principal:

**Prezes Urzędu Ochrony Danych Osobowych (UODO)**  
ul. Stawki 2, 00-193 Warsaw, Poland  
Website: https://uodo.gov.pl

---

## 12. Cambios en esta Política
Podemos actualizar esta Política de Privacidad periódicamente para reflejar cambios en nuestras prácticas o en las leyes aplicables. Le notificaremos sobre cambios publicando la nueva Política de Privacidad en la Aplicación o en nuestro repositorio.

Si realizamos cambios materiales en la forma en que procesamos sus datos (por ejemplo, cambiando la arquitectura local-first), proporcionaremos un aviso más destacado, como una notificación en la aplicación, antes de que los cambios entren en vigor.

---

## 13. Contáctenos
Para cualquier pregunta relacionada con la privacidad o para ejercer sus derechos de datos, póngase en contacto con el Responsable del Tratamiento:

**Email:** wottomekr@gmail.com
*La dirección postal completa y detalles adicionales de identificación están disponibles previa solicitud por escrito de conformidad con el Artículo 13 del GDPR.*

