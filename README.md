# Expedientes Médicos PWA v3

Aplicación web instalable para registrar pacientes, medicamentos, controles, documentos, tratamientos y consultas. Incluye pantalla de identificación, perfil con foto o logotipo y clave local de acceso.

La versión 3.2 permite asignar hasta seis horas exactas diarias a cada medicamento y muestra una alerta visual, sonora y del navegador en cada hora programada mientras la aplicación permanece abierta.

La versión 3.3 agrega una agenda independiente de citas médicas con fecha y hora, médico, especialidad, lugar, teléfono, motivo, estado, edición, eliminación y listado de próximas citas.

La versión 3.4 incorpora la pestaña Consulta/visitas al médico con nombre del médico, fecha y hora, molestias o dolencias, diagnóstico, recomendaciones, próxima cita y lugar.

Los datos se guardan localmente en el navegador. Los registros usan localStorage y los archivos adjuntos usan IndexedDB.

Para probarla localmente, sirve la carpeta `dist` mediante un servidor HTTP. No abras el HTML directamente si deseas probar la instalación PWA y el modo sin conexión.
