# NEXTGEN-EDU

Este repositorio contiene el código fuente de la aplicación para la gestión de tareas y el monitoreo en tiempo real de los estudiantes del programa PTVAL. Este proyecto se desarrolla como parte del máster en Ingeniería Informática, con el objetivo de mejorar la autonomía de los estudiantes y proporcionar herramientas útiles para los educadores.

---

## **Estrategia de Ramas**

Estamos utilizando el modelo de ramas **Git Flow** para gestionar el flujo de desarrollo.

- **Main**: Contiene el código estable y listo para producción.
- **Develop**: Consolida las funcionalidades completadas para la siguiente versión.
- **Ramas de características**: Se utilizan para desarrollar nuevas funcionalidades o tareas específicas.

### **Descripción de Tareas**

#### **Tarea 1: Implementar el Módulo de Gestión de Tareas**
- **Descripción**: Desarrollo de la funcionalidad para que los estudiantes gestionen sus tareas diarias.
- **Responsable**: Álvaro Ordóñez Romero
- **Miembros del equipo**: 
  - Álvaro (rama secundaria: `feature/task-management_alvaro`)
  - Smail (rama secundaria: `feature/task-management_smail`)

#### **Tarea 2: Integrar Monitoreo de Geolocalización**
- **Descripción**: Agregar seguimiento en tiempo real de la ubicación de los estudiantes para los educadores.
- **Responsable**: Smail Dahmani
- **Miembros del equipo**: 
  - Álvaro (rama secundaria: `feat/geolocation_alvaro`)
  - Smail (rama secundaria: `feat/geolocation_smail`)

---

## **Proceso de Desarrollo**

### 1. Inicialización de Tareas
- Cada tarea se desarrolla en una **rama de características** (por ejemplo, `feat/task-management`).
- Los miembros del equipo crean sub-ramas para simular el trabajo en paralelo.

### 2. Flujo de Contribución
- Cada desarrollador realiza commits en su sub-rama.
- Después de completar su trabajo, los miembros del equipo fusionan sus sub-ramas en la rama principal de la característica.

### 3. Finalización de Tareas
- El responsable de cada tarea fusiona la rama de la característica en `staging` y, finalmente, en `main`.

---

## **Etiquetas**
- `v1.0.0`: Primera versión, incluye gestión de tareas y monitoreo por geolocalización.
- `v1.1.0`: Incluye correcciones de errores y actualizaciones menores.

---

## **Integración con Jira**
Este repositorio está vinculado a un proyecto en Jira para la gestión de incidencias. Los commits se etiquetan con la clave de la incidencia en Jira, asegurando la trazabilidad entre el código y las incidencias.

---

## **Colaboradores**
- **Álvaro Ordóñez Romero**: Desarrollador, Diseñador de UI
- **Smail Dahmani**: Desarrollador, Tester, Gestor de Incidencias
