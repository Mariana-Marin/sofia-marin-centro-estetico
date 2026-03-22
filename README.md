# Sofía Marín - Centro Estético

Una aplicación web integral ("Single Page Application") diseñada específicamente para la gestión clínica y operativa de un centro de cosmetología y estética. La herramienta digitaliza el flujo de trabajo de la profesional, desde el ingreso del paciente hasta las indicaciones de cuidado en casa.

## Funcionalidades Principales

- **Sistema de Acceso Seguro**: Autenticación rápida mediante un PIN predeterminado (1234).
- **Dashboard de Métricas**: Panel de control con estadísticas del día (total de pacientes, sesiones de hoy, distribución facial/corporal) y lista de pacientes frecuentes o VIP.
- **Asistente de Fichas (6 Pasos)**:
  1. **Tipo de Consulta**: Selección entre tratamientos corporales o faciales, y registro de citas recurrentes.
  2. **Datos Personales**: Recopilación de información general y antropométrica.
  3. **Diagnóstico Clínico**: Registro del estado de piel, condiciones a tratar, alergias y zona aplicada.
  4. **Sugerencias mediante Inteligencia Artificial**: Integración automatizada con de LLMs para recomendar tratamientos base.
  5. **Consentimiento Informado**: Lectura y aceptación digital legal por parte del usuario.
  6. **Post-Tratamiento Automático**: Generación rápida de recomendaciones personalizadas por IA para copiar y enviar al cliente por WhatsApp.
- **Historial Profesional**: Función de vistas previas de sesiones pasadas y perfil detallado de cada paciente.
- **Persistencia**: Incluye modo offline/híbrido por LocalStorage en el navegador con soporte adaptable a Firebase Cloud Firestore.

## Stack Tecnológico

- HTML5, CSS3 puro (variables CSS, flexbox, grid nativo) y Vanilla JS.
- Utiliza la API de Anthropic.
- Adaptado para integraciones Firebase Auth y Firestore.

## Uso Rápido

1. Clonar este repositorio localmente.
2. Abrir el archivo index.html en tu navegador.
3. Ingresa tu PIN de entrada y disfruta tu aplicación de gestión.
