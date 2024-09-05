# BATTLESHIP - DPOO - 2021/2022

Este proyecto es una versión retro del clásico juego "Hundir la flota", desarrollado como parte de la asignatura de Diseño y Programación Orientado a Objetos (DPO) utilizando Java y la librería gráfica Swing. El objetivo principal del juego es hundir los barcos enemigos antes de que ellos destruyan los tuyos. A diferencia del juego tradicional, en esta versión te enfrentarás a una Inteligencia Artificial (IA), pudiendo combatir hasta con 4 enemigos a la vez.

## **Características principales**
- **Juego para un jugador**: Enfréntate a la IA con opciones de dificultad variadas.
- **Batallas en tiempo real**: No hay turnos estáticos, los ataques dependen de la recarga de tus cañones.
- **IA avanzada**: La IA coloca estratégicamente sus barcos y responde a tus ataques.
- **Multijugador contra IA**: Posibilidad de enfrentarte a hasta 4 enemigos al mismo tiempo.
- **Opciones de guardado y carga**: Guarda tus partidas y continúa desde donde lo dejaste.
- **Estadísticas de usuario**: Revisa tus logros, partidas jugadas y otros datos de rendimiento.

## **Tecnologías utilizadas**
- **Lenguaje de programación**: Java
- **Interfaz gráfica**: Swing (Java)
- **Base de datos**: MySQL
- **Patrón de diseño**: Modelo-Vista-Controlador (MVC)
- **Arquitectura**: Arquitectura por capas

## **Instalación**
### Requisitos
- Java SE 18 o superior.
- MySQL para la base de datos de usuarios y partidas.
- Maven para la gestión de dependencias (opcional).

### Instrucciones
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
   ```
2. Importa el proyecto en tu IDE de preferencia (IntelliJ IDEA, Eclipse, etc.).
3. Configura la base de datos MySQL:
    - Crea una base de datos nueva para el juego.
    - Ejecuta el script SQL incluido en la carpeta `/db` para crear las tablas necesarias.
    - Modifica el archivo de configuración (`resources/config.json`) con los detalles de conexión a tu base de datos.
4. Ejecuta el archivo `Main.java` para iniciar el juego.

## **Cómo jugar**
- Inicia sesión o regístrate en la aplicación.
- Accede al menú principal donde podrás:
    - Iniciar una nueva partida.
    - Cargar una partida guardada.
    - Revisar tus estadísticas.
    - Ajustar configuraciones.
- Durante la partida:
    - Coloca tus barcos en el tablero.
    - Ataca las posiciones enemigas mientras esperas a que tus cañones se recarguen.
    - Gana el juego destruyendo todos los barcos enemigos.

## **Estructura del proyecto**
El proyecto sigue una arquitectura por capas que se divide en:
1. **Capa de Presentación**: Gestiona la interfaz gráfica y la interacción del usuario.
2. **Capa de Business**: Contiene la lógica del juego y maneja las reglas y dinámicas.
3. **Capa de Persistencia**: Se encarga del almacenamiento de datos en la base de datos y en archivos locales (JSON para partidas guardadas).

## **Licencia**
Este proyecto está bajo la licencia, consulta el archivo `LICENSE` para más detalles.

---
