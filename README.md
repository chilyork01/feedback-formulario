# feedback-formulario# Formulario de Feedback

Este documento proporciona detalles sobre cómo configurar y utilizar el formulario de feedback en tu aplicación web. Este formulario permite a los usuarios enviar comentarios y sugerencias directamente a través de WhatsApp.

## Descripción

El formulario de feedback está diseñado para recopilar la información de los usuarios, incluyendo su nombre, correo electrónico y mensaje. Los datos del formulario se envían a un número de teléfono de WhatsApp específico mediante un enlace preformateado.

## Cómo Funciona

1. **Recopilación de Datos**: Los usuarios completan los campos de nombre, correo electrónico y mensaje.
2. **Envío de Feedback**: Al hacer clic en el botón "Enviar Feedback", se abre WhatsApp Web o la aplicación móvil con un mensaje preescrito que incluye los detalles del formulario.
3. **Número de WhatsApp**: Asegúrate de reemplazar el número de teléfono en el código con el número al que deseas recibir el feedback.

## Instrucciones para Usar el Formulario

1. **Configuración del Número de WhatsApp**:
   - Abre el archivo `index.html` del formulario de feedback.
   - Reemplaza `'1234567890'` en el código JavaScript con tu número de teléfono completo, incluyendo el código de país (sin signos de más ni espacios).

2. **Integración del Formulario en tu Proyecto**:
   - Copia el código HTML del formulario en tu proyecto web.
   - Asegúrate de que el archivo `index.html` esté correctamente vinculado en tu aplicación.

3. **Probar el Formulario**:
   - Abre el archivo `index.html` en un navegador.
   - Completa el formulario y haz clic en "Enviar Feedback" para verificar que se abre WhatsApp con el mensaje preescrito.
