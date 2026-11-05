# Agenda (Android Studio)

App de agenda hecha con Jetpack Compose que implementa un CRUD usando un diccionario
reactivo (`mutableStateMapOf<Int, Persona>`).

## Funcionalidades
- **Create:** agrega una persona con ID, nombre y edad.
- **Read:** lista todos los registros ordenados por ID.
- **Update:** el botón de editar carga los datos en el formulario; el ID queda bloqueado.
- **Delete:** elimina el registro por su clave.
- Validación: muestra un error si algún campo está vacío o no es numérico donde corresponde.

## Tecnologías
Kotlin · Jetpack Compose · Material 3

## Cómo ejecutarlo
1. Clonar el repositorio.
2. Abrir la carpeta en Android Studio y esperar el *Gradle Sync*.
3. Ejecutar en un emulador o dispositivo (Run ▶).
