Módulo de Transporte y Logística para Odoo

Autor: Carlos Andrés Ayllón Canales
Fecha: Febrero 2025
Versión: 1.0
Tecnologías: Python · Odoo Framework · XML

📖 Descripción

Este proyecto consiste en el desarrollo de un módulo personalizado para Odoo orientado a la gestión de transporte y logística, permitiendo administrar camiones, remolques, reparaciones y avisos de revisión.
El objetivo principal es optimizar la gestión de flotas, facilitando el control de mantenimiento, costes y asignaciones de vehículos.

⚙️ Funcionalidades principales
🚛 Modelo de Camión

Registro de información básica (nombre, modelo, matrícula).

Seguimiento de kilómetros recorridos y mantenimientos.

Cálculo automático del coste total de reparaciones y del promedio de kilómetros diarios.

Relaciones:

One2many con Reparaciones.

Many2many con Remolques.

🛞 Modelo de Remolque

Gestión de datos de cada remolque.

Asociación Many2many con camiones activos.

🔧 Modelo de Reparación

Control detallado de intervenciones técnicas.

Campos: descripción, fecha, coste y camión asociado.

🧾 Modelo de Aviso de Revisión

Gestión de revisiones programadas.

Control por fechas y kilometraje.

Permite asegurar revisiones periódicas y cumplimiento de mantenimiento.

🔒 Seguridad y Roles

El módulo incluye roles y permisos personalizados:

Usuario de Transporte: acceso a visualización de datos generales.

Gerente de Transporte: permisos completos para crear, editar y gestionar registros.

🧩 Instalación y Pruebas

Crear una base de datos limpia en Odoo.

Instalar el módulo desde la interfaz principal (sin necesidad de modo desarrollador).

Activar los grupos de permisos incluidos.

Probar la creación y gestión de camiones, remolques y reparaciones.

Durante las pruebas se validaron los campos calculados, vistas Kanban y Form, y el correcto funcionamiento de las relaciones entre modelos.

🧠 Aprendizajes y Conclusiones

El desarrollo de este módulo permitió:

Profundizar en el uso del framework de Odoo y su ORM.

Mejorar el dominio de Python aplicado al desarrollo empresarial.

Practicar la gestión de modelos, relaciones, roles y vistas personalizadas.

El proyecto fomentó la autonomía, investigación y resolución de errores, enfrentando problemas reales como fallos de instalación, errores de carga o conflictos en vistas XML.

💡 Sugerencias de mejora

Implementar notificaciones automáticas para los avisos de revisión.

Integrar Google Maps para calcular rutas óptimas según tráfico o distancia.

Añadir lógica de optimización de carga según tipo de camión o remolque.

🔗 Referencias

Odoo Documentation – Computed Fields

Odoo ORM Reference

A2Systems – Relaciones One2many / Many2many

👨‍💻 Autor

Carlos Andrés Ayllón Canales
Desarrollador de software | Especializado en desarrollo de Aplicaciones
📅 Proyecto académico – 2º DAMA (Desarrollo de Aplicaciones Multiplataforma)
