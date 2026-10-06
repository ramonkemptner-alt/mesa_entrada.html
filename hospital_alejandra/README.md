# Hospital de Alejandra

Versión premium de un sistema de atención hospitalaria diseñado para mejorar la experiencia del paciente, optimizar la organización de turnos y agilizar la atención en recepción.

> Nota: el logo institucional del hospital puede agregarse más adelante según la identidad visual definitiva. Por el momento, el proyecto incluye un branding premium y editable con espacio para incorporar el logo oficial.

## Autor

Ramon Fernando Daniel Kemptner

## Descripción

Este proyecto presenta una interfaz moderna para una mesa de entrada hospitalaria, diseñada para facilitar:

- La emisión de turnos de atención
- La validación de pacientes mediante QR
- La evaluación inicial de triaje
- La búsqueda de turnos por documento
- La orientación visual del hospital mediante mapa de servicios
- La gestión operativa desde un panel de recepción

The system is designed to be used on a public touch screen, on an internal administrative panel and on desktop and tablet computers, maintaining a functional and consistent experience on different devices.

## Funcionalidades principales

- Dashboard de bienvenida para pacientes
- Generación automática de tickets con código QR
- Escaneo de código QR por cámara o ingreso manual
- Evaluación de urgencias y prioridad
- Consulta de turnos por DNI
- Mapa del hospital con sectores y servicios
- Panel administrativo para atención y control de cola
- Reloj en tiempo real y diseño responsivo

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- Font Awesome
- QRCode.js
- HTML5-QRCode

## Requisitos

- Navegador web moderno
- Conexión a internet para cargar librerías externos

## Instalación y uso

1. Descarga o clona el repositorio.
2. Abre el archivo `mesa_entrada.html` en tu navegador.
3. La aplicación mostrará la interfaz principal del sistema.
4. Puedes navegar entre el modo paciente y el panel de recepción.

## Estructura del proyecto

- `mesa_entrada.html` — Archivo principal de la aplicación
- `README.md` — Documentación del proyecto

## Objetivo del proyecto

Reducir tiempos de espera, mejorar la organización de la atención y brindar una experiencia más clara y accesible para pacientes y personal hospitalario.

## Política de duración de turnos

Para optimizar el uso de la base de datos y mantener la cola ordenada, los turnos se eliminan automáticamente según la siguiente lógica:

- Si un turno se genera durante fin de semana, queda registrado hasta el día lunes.
- Si un turno se genera entre lunes y viernes, tiene una vigencia de 24 horas.
- Luego de ese tiempo, el turno se elimina del sistema para evitar registros obsoletos y ahorrar almacenamiento.
- Esta regla está pensada exclusivamente para agilizar y mantener liviana la gestión de turnos del hospital.

## Estado del proyecto

Proyecto funcional de demostración en desarrollo.

## Licencia

Proyecto para uso interno, demostración y presentación personal, salvo indicación contraria del autor.

## Contacto

Ramon Fernando Daniel Kemptnerr

                    <div class="relative w-14 h-14 rounded-2xl bg-gradient-to-br from-hospital-600 via-hospital-700 to-medical-teal text-white flex items-center justify-center shadow-lg shadow-hospital-500/30 ring-4 ring-white">

Desarrollado con enfoque en atención médica digital, usabilidad y experiencia del paciente.

<div class="w-12 h-12 rounded-xl border-2 border-dashed border-slate-300 bg-slate-100 text-slate-500 flex items-center justify-center shadow-sm">
                    <div class="max-w-3xl relative z-10 space-y-3">
