# TFG-LifeGoals

Trabajo de Fin de Grado (DAM) desarrollado como una plataforma de gestión de objetivos personales asistida por Inteligencia Artificial.

La aplicación permite a los usuarios crear metas, organizar su progreso y generar automáticamente planes de acción mediante Google Gemini AI.

## Características

- Registro e inicio de sesión mediante Firebase Authentication.
- Gestión de objetivos personales.
- Seguimiento del progreso mediante hitos.
- Generación automática de planes de acción con Google Gemini.
- Sincronización en tiempo real mediante Firestore.
- Aplicación web y aplicación móvil.

## Tecnologías utilizadas

### Frontend Web
- React
- TypeScript
- Vite
- Tailwind CSS
- React Router

### Aplicación Móvil
- React Native

### Backend y Servicios
- Firebase Authentication
- Cloud Firestore
- Google Gemini AI

## Arquitectura

<img width="1440" height="1040" alt="image" src="https://github.com/user-attachments/assets/e848efd9-6d10-48dc-b0a5-6173e5149f35" />

## Funcionalidades principales

### Gestión de metas
Los usuarios pueden crear, editar y eliminar objetivos personales.

### Planificación con IA
A partir de una descripción del objetivo, Gemini genera automáticamente una serie de hitos para facilitar su cumplimiento.

### Seguimiento del progreso
Cada meta dispone de hitos completables que actualizan el porcentaje de progreso en tiempo real.

## Demo

Se incluye una demostración en vídeo del funcionamiento completo de la aplicación:



## Configuración

El proyecto utiliza Firebase y Google Gemini.

Por motivos de seguridad, las credenciales y claves API no se incluyen en este repositorio.

Para ejecutar el proyecto es necesario configurar:

- Firebase Authentication
- Cloud Firestore
- API Key de Google Gemini
