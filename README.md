# Tarea 1 - Generador de Mapas de Dungeon

### Instrucciones Básicas para Ejecutar el Código

1.  **Requisitos**: Asegúrate de tener Python 3.8 o superior instalado.
2.  **Instalar dependencias**: El proyecto utiliza las librerías `rich` y `PyYAML`. Instálalas con `pip`:
    ```bash
    pip install rich pyyaml
    ```
3.  **Ejecutar el juego**: Desde la carpeta principal del proyecto, ejecuta el archivo `main.py`:
    ```bash
    python main.py
    ```

---

### Descripción del Diseño e Implementación

El proyecto implementa un generador de mapas para dungeons utilizando Programación Orientada a Objetos (POO). El diseño se basa en las siguientes clases:

* **`Mapa`**: Gestiona la creación de la estructura del dungeon, asegurando que todas las habitaciones sean accesibles desde la inicial.
* **`Habitacion`**: Representa un nodo en el mapa, con coordenadas, conexiones y un contenido que puede ser explorado.
* **`Explorador`**: Representa al jugador, con vida, inventario y la capacidad de moverse.
* **`ContenidoHabitacion`** (abstracta): Sirve como base para diferentes tipos de contenido (`Tesoro`, `Monstruo`, `Jefe`, `Evento`) que tienen su propia lógica de interacción.
* **`Visualizador`**: Utiliza la librería `rich` para mostrar el estado del juego de forma clara.

---

### Cumplimiento de Requerimientos

| Requerimiento | Estado | Observación |
| :--- | :--- | :--- |
| 1. Clase `Habitacion` | Cumplido | |
| 2. Clase `Mapa` | Cumplido | |
| 3. Clase `Objeto` | Cumplido | |
| 4. Clase `Explorador` | Cumplido | |
| 5. Clase `ContenidoHabitacion` | Cumplido | |
| 6. Reglas de Contenido | Cumplido | |
| 7. Estadísticas del Mapa | Cumplido | |
| 8. Serialización | Cumplido | |
| 9. Visualizador | Cumplido | |
| 10. Sistema de Eventos | Cumplido | |
| 11. Dificultad Escalable | Cumplido | |
