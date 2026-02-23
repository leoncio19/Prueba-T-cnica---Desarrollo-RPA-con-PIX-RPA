# Prueba Técnica - Desarrollo RPA con PIX Studio

## Descripción del proyecto
Este proyecto consiste en un robot de software (RPA) desarrollado sobre la plataforma PIX Robotics para automatizar el ciclo de vida de datos de productos de una tienda online. El robot realiza la extracción de datos desde una API pública, su respaldo en formato JSON, el almacenamiento estructurado en una base de datos local, la generación de reportes analíticos en Excel y la distribución final mediante OneDrive y formularios web  y captura una evidencia visual del envío exitoso.

## Pasos para ejecución
Configuración de Credenciales:

1. Asegúrese de tener configuradas las variables de entorno o el archivo de configuración con el client_id y client_secret de la API de Microsoft Graph para la conexión con OneDrive.

Preparación de Entorno:

1. Verificar que la base de datos SQLite exista en la ruta: C:\*****\PIX ROBOTICS\BD\pix_bd.db.

2. Asegurarse de que las carpetas LOGS, REPORTES y Evidencias estén creadas.


Ejecución en PIX Studio:

1. Abrir el proyecto en PIX Studio v2.27.3.

2. Conectar el Studio al Master para habilitar todas las actividades.

3. Presionar el botón "Ejecutar" (Run).

Verificación:

1. El robot generará un log en LOGS/Productos_YYYY-MM-DD.json.

2. Se creo el reporte en REPORTES/Reporte_YYYY-MM-DD.xlsx.

3. El formulario de google esta debidamente diligenciado y el archivo excel alojado en la unidad de google drive 

4. Al finalizar, se guardará una captura de pantalla del formulario enviado en la carpeta Evidencias

## Requisitos o dependencias
Software:

1. PIX Studio v2.27.3.
2. Motor de Base de Datos MYsql.
3. Navegador Web Chrome para la automatización del formulario.
   
Conectividad:

1. Acceso a Internet para consumo de la Fake Store API (https://fakestoreapi.com/products).
2. Acceso a los servicios de Microsoft Graph API.

Librerías/Actividades:

1. PIX Master conectado para uso de licencias completas

## 🔗 Enlaces Importantes
**Enlace del formulario usado:** https://docs.google.com/forms/d/e/1FAIpQLSeSAL06oNvTLrByB_4w7EB4QcaAjnC_HcrbzsoMW2TE7o1FeA/viewform
**Video explicativo de la ejecución:** https://www.youtube.com/watch?v=M0GOECpz8Ag
