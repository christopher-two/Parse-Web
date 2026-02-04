# **Política de Privacidad de Parse**

**Última actualización:** 03 de Febrero de 2026

Esta Política de Privacidad describe cómo **Parse** ("nosotros", "nuestro" o "la aplicación"), desarrollada por Christopher, recopila, utiliza y comparte información sobre usted cuando utiliza nuestra aplicación móvil.

Parse está diseñada con un enfoque en la privacidad. **No vendemos sus datos personales a terceros.**

## **1\. Información que recopilamos**

### **1.1. Información proporcionada por el usuario (Autenticación)**

Para ofrecer una experiencia personalizada y segura, utilizamos **Google Sign-In** a través de Firebase Authentication. Cuando inicias sesión, podemos recopilar y almacenar la siguiente información básica asociada a tu cuenta de Google:

- Dirección de correo electrónico.
- Nombre y foto de perfil (si están disponibles públicamente).
- Identificador único de usuario (UID de Firebase).

### **1.2. Archivos y Documentos (Libros)**

Parse es una aplicación de lectura. Para funcionar, la aplicación requiere acceso a los archivos (libros en formato PDF) almacenados en su dispositivo.

- **Procesamiento Local:** Todo el procesamiento de los libros (renderizado de páginas, extracción de texto, generación de portadas) se realiza **localmente en su dispositivo**.
- **Sin Subida a Servidores:** Nosotros **no subimos** sus libros ni documentos a ningún servidor externo. Su biblioteca personal permanece privada en su dispositivo.

### **1.3. Datos técnicos y de uso (Crashlytics)**

Utilizamos herramientas para mejorar la estabilidad de la aplicación. Recopilamos automáticamente cierta información cuando se produce un error o "crasheo":

- Datos de registro de fallos (Stack traces).
- Información del dispositivo (Modelo, versión de Android, orientación de pantalla).
- **Nota:** Estos datos son anónimos y se utilizan únicamente para corregir errores.

### **1.4. Inteligencia Artificial y Machine Learning**

La aplicación utiliza tecnologías de aprendizaje automático para mejorar su funcionalidad.

- **Procesamiento 100% Local:** Utilizamos modelos locales (como **ML Kit**) que se ejecutan directamente en el hardware de su dispositivo. **No enviamos** ningún dato a servidores externos para ser procesado por funciones de IA. Toda la información analizada permanece en su teléfono.
- **Control del Usuario:** En el caso hipotético de que en el futuro se implementen funciones que requieran procesamiento en la nube, estas estarán desactivadas por defecto. Usted tendrá el control total para activarlas o desactivarlas manualmente desde la sección "Funciones de IA" en la configuración de su cuenta.

## **2\. Cómo utilizamos su información**

Utilizamos la información recopilada para los siguientes fines:

1. **Autenticación:** Para verificar su identidad y permitir el acceso a la aplicación.
2. **Funcionalidad Principal:** Para permitirle abrir, leer y gestionar sus libros locales.
3. **Mejora de la App:** Utilizamos los datos de fallos (Crashlytics) para identificar y solucionar problemas técnicos.
4. **Sincronización (Estado Local):** El progreso de lectura se almacena únicamente en una base de datos local (Room) dentro de su dispositivo.
5. **Comunicaciones Legales:** Podemos utilizar su dirección de correo electrónico para enviarle notificaciones importantes sobre cambios en esta Política de Privacidad o en nuestros Términos y Condiciones.

## **3\. Permisos de Android**

La aplicación puede solicitar los siguientes permisos para funcionar:

- **Acceso a Archivos:** Mediante el selector del sistema (Storage Access Framework) para permitirle leer PDFs locales.
- **Acceso a Internet:** Necesario únicamente para la autenticación con Google y el reporte de errores anónimos.

## **4\. Servicios de Terceros**

La aplicación utiliza servicios de terceros que pueden recopilar información utilizada para identificarle:

- [Google Play Services](https://policies.google.com/privacy)
- [Firebase Auth](https://firebase.google.com/support/privacy)
- [Firebase Crashlytics](https://firebase.google.com/support/privacy)
- [Google ML Kit](https://developers.google.com/ml-kit/terms)

## **5\. Retención y Eliminación de Datos**

### **5.1. Derecho a la Eliminación**

Usted tiene derecho a solicitar la eliminación de su cuenta y de todos los datos personales asociados en cualquier momento.

### **5.2. Procedimiento de Eliminación**

Puede solicitar la eliminación total de sus datos de dos maneras:

1. **Dentro de la aplicación:** Accediendo a la sección de **Configuración \> Cuenta \> Eliminar cuenta**. Esta acción eliminará su perfil de autenticación de forma inmediata.
2. **A través de la web (Soporte):** Si ya no tiene instalada la aplicación, puede visitar nuestro [Sitio de Soporte y Eliminación de Datos](https://www.google.com/search?q=https://parse.christopher.com.mx/support) o enviar un correo electrónico a **christopher.cop787@gmail.com** con el asunto "Eliminación de cuenta".

### **5.3. Qué datos se eliminan**

Al procesar una solicitud de eliminación, se borrará permanentemente de nuestros sistemas de autenticación:

- Su dirección de correo electrónico.
- Su identificador único de usuario (UID).
- Metadatos del perfil de Google asociados a la app.  
  _Nota: Los archivos PDF locales de su dispositivo no se verán afectados, ya que nosotros nunca tuvimos acceso a ellos fuera de su terminal._

## **6\. Seguridad**

Valoramos su confianza al proporcionarnos su información personal, por lo que nos esforzamos por utilizar medios comercialmente aceptables para protegerla. Los datos en tránsito se cifran mediante protocolos estándar de la industria.

## **7\. Contacto**

Si tiene alguna pregunta sobre la eliminación de sus datos o esta política, contáctenos en:

- **Correo electrónico:** christopher.cop787@gmail.com
- **Sitio Web:** https://www.google.com/search?q=https://parse.christopher.com.mx
