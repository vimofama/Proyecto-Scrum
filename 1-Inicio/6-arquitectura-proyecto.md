# Arquitectura del producto

## 1. Interfaz de Usuario (UI):

* Responsabilidades:
    - Interacción con el usuario a través de la línea de comandos.
    - Muestra resultados de traducción y mensajes de error.
* Tecnología:
    - Biblioteca estándar de Python para entrada/salida (por ejemplo, input() y print()).

## 2. Controlador (Controller):

* Responsabilidades:
    - Recibe la entrada del usuario.
    - Valida la entrada.
    - Coordina las llamadas a la lógica de traducción.
* Tecnología:
    - Python estándar para la programación estructurada.

## 3. Lógica de Traducción (Translation Logic):

* Responsabilidades:
    - Traduce el número ingresado a kichwa.
    - Devuelve el resultado de la traducción.
* Tecnología:
    - Puedes implementar esta lógica en Python sin necesidad de bibliotecas externas.

## 4. Manejo de Errores y Excepciones (Error Handling):

* Responsabilidades:
    - Maneja errores y excepciones.
    - Proporciona mensajes de error claros al usuario.
* Tecnología:
    - Python proporciona capacidades de manejo de excepciones incorporadas que puedes utilizar para este propósito.

## 5. Gestión del Flujo de la Aplicación (Application Flow Control):

* Responsabilidades:
    - Coordina el flujo general de la aplicación.
    - Decide cuándo mostrar la traducción, cómo manejar los errores y cuándo finalizar la ejecución según la decisión del usuario.
* Tecnología:
    - Implementado en Python estándar con estructuras de control de flujo como if, while, y funciones.

## 6. Persistencia de Datos (Data Persistence):

* Responsabilidades:
    - Almacena y recupera datos (por ejemplo, registros de traducciones anteriores, configuración).
* Tecnología:
    - Puedes utilizar bibliotecas de Python como sqlite3 para bases de datos SQL o pickle para almacenamiento de datos en archivos.