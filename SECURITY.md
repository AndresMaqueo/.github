📌 Política de Seguridad para Microsoft Teams (Avanzada y Sofisticada)
✅ Objetivo
Garantizar la seguridad, integridad y cumplimiento de Microsoft Teams sin afectar la colaboración ni la experiencia de los usuarios. Se enfoca en protección avanzada contra amenazas, control de acceso granular, auditoría en tiempo real y optimización del rendimiento.

🔒 1. Control de Acceso Seguro
🔹 Autenticación y Autorización
✔ Requerir autenticación multifactor (MFA):

Implementar MFA obligatoria para administradores y usuarios clave.
Usar Azure AD Conditional Access para exigir MFA en ubicaciones o dispositivos desconocidos.
✔ Integración con Entra ID (Azure AD) para autenticación única (SSO) y administración centralizada.
✔ Deshabilitar autenticación heredada para evitar ataques de fuerza bruta.
🔹 Gestión de Dispositivos y Sesiones
✔ Habilitar Microsoft Defender for Endpoint para monitorear dispositivos.
✔ Configurar acceso condicional para permitir solo dispositivos gestionados o seguros.
✔ Definir un límite de sesión en Teams para cerrar sesiones inactivas y reducir el riesgo de acceso no autorizado.

🔍 2. Protección de Información Sensible
🔹 Prevención de Fugas de Datos (DLP)
✔ Bloquear el uso de datos sensibles en Teams con Microsoft Purview DLP.
✔ Crear reglas para restringir la compartición de archivos confidenciales (ej. Finanzas, Contratos, Datos Personales).
✔ Auditoría en tiempo real para detectar y prevenir filtraciones de datos.

🔹 Clasificación y Cifrado de Datos
✔ Configurar etiquetas de sensibilidad en Microsoft Purview para cifrar y restringir acceso.
✔ Obligar cifrado de extremo a extremo en reuniones con información crítica.

🛡️ 3. Protección contra Amenazas
🔹 Monitoreo y Respuesta Automática
✔ Habilitar Microsoft Defender for Office 365 para detectar y bloquear ataques de phishing y malware en chats y archivos.
✔ Activar detección de amenazas en Teams con Microsoft Sentinel para identificar patrones de comportamiento sospechosos.
✔ Crear alertas de seguridad avanzadas para inicios de sesión anómalos, intentos de acceso desde IPs sospechosas y modificaciones de configuración críticas.

🏢 4. Gestión de Permisos y Privilegios
✔ Aplicar el principio de privilegio mínimo (PoLP) para administradores y usuarios.
✔ Restringir creación de Teams públicos a usuarios autorizados.
✔ Bloquear la invitación de usuarios externos a menos que se apruebe por IT.
✔ Habilitar revisiones automáticas de permisos en Microsoft Entra.

🛠️ 5. Configuración Avanzada de Teams
✔ Bloquear aplicaciones no autorizadas en Teams con Microsoft App Governance.
✔ Habilitar restricciones en reuniones y canales para prevenir acceso no autorizado.
✔ Auditar y restringir el acceso de bots y conectores externos.

📊 6. Auditoría y Cumplimiento
✔ Activar registros de auditoría en Microsoft Purview para monitorear cambios críticos.
✔ Habilitar el Centro de Cumplimiento para reportes de seguridad y análisis de vulnerabilidades.
✔ Automatizar la revisión de políticas para detectar desviaciones en la seguridad.
