# 🏥 Asistente Virtual Clínico

📌 Sobre el Proyecto

Este proyecto es una herramienta web interactiva (Single Page Application) diseñada para optimizar el flujo de trabajo de los asistentes administrativos en clínicas dermatológicas o centros de salud.

El objetivo principal es transformar un "manual de respuestas" estático en una herramienta de alto rendimiento que permita responder mensajes de WhatsApp de forma rápida, empática y estandarizada, reduciendo el margen de error y mejorando la tasa de conversión de pacientes.

🚀 Características Principales (MVP)

Arquitectura Cognitiva: Layout de dos columnas que separa las Reglas de Negocio (protocolos internos) de la Acción (guiones de respuesta).

Personalización Dinámica: Inyección de nombres en tiempo real en todos los guiones mediante un input central, eliminando la edición manual.

Sistema de Rescate (Técnica RCP): Guiones específicos para seguimiento de pacientes que no han respondido o necesitan agendar citas de control.

Portapapeles Universal: Botones de copia rápida que formatean el texto correctamente para WhatsApp.

Diseño Responsivo: Interfaz adaptada a dispositivos móviles con menú Off-Canvas para acceso rápido a protocolos.

🛠️ Tecnologías Utilizadas

HTML5

Tailwind CSS (vía CDN)

JavaScript (Vanilla)

Lucide Icons

🧠 Metodología y Uso de Inteligencia Artificial

Este proyecto fue desarrollado utilizando un enfoque de Pair Programming con Inteligencia Artificial (Google Gemini).

El proceso de desarrollo siguió estas fases:

Análisis de Requerimientos (Humano): Identifiqué un problema real en el flujo de trabajo clínico (respuestas robóticas, desorganización de precios, pérdida de tiempo copiando y pegando).

Arquitectura de la Información (Humano + IA): Basándome en metodologías de ventas por WhatsApp (ej. Método Steph Jara), estructuré las respuestas pasando de "dar precios" a "conectar y diagnosticar".

Desarrollo Frontend (IA guiada por Humano): Utilicé Gemini para generar el código base en HTML y Tailwind CSS, iterando mediante prompts específicos para pulir la UI/UX.

Refinamiento de UX/UI (Humano): Solicité implementaciones clave para el rendimiento real del usuario, como:

Ocultar barra de navegación en scroll.

Crear la funcionalidad de inyección dinámica de nombres (JavaScript).

Mejorar la accesibilidad móvil.

Implementar métodos de copiado seguros (document.execCommand).

Conclusión: La IA funcionó como un acelerador de código (developer tool), permitiéndome enfocarme en la lógica del negocio, la experiencia del usuario final y la resolución del problema real.

💡 Cómo usar este repositorio

Clona este repositorio o descarga el archivo index.html.

Abre index.html en cualquier navegador web moderno.

¡Listo! No requiere instalación de dependencias ni servidores locales.

Desarrollado por Tomás De la Cruz Segura
