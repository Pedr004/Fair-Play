
[TDD-4.pdf](https://github.com/user-attachments/files/19347460/TDD-4.pdf)

Lista de características obtenidas del GDD 
Gameplay inspirado en "Papers, Please": 
● Revisión de tareas de estudiantes para detectar el uso indebido de IA. 
● Mecánica de evaluación basada en la detección de irregularidades en los 
documentos. 
● Herramientas de detección de IA y plagio que se desbloquean 
progresivamente. 
Interacción en el aula (novela visual): 
● Diálogos con estudiantes para enseñar el uso responsable de la IA. 
● Decisiones que afectan el comportamiento y ética de los alumnos. 
Gestión financiera: 
● Administración del salario del profesor para cubrir gastos diarios (alquiler, 
comida, etc.). 
● Recompensas económicas basadas en el desempeño de los estudiantes. 
Progresión y dificultad: 
● Aumento de la complejidad a medida que avanza el semestre. 
● Más estudiantes usan IA, algunos de manera adecuada y otros para hacer 
trampa. 
Interfaz minimalista y funcional: 
● Menú principal, interfaz de trabajo, interfaz de clases y gestión financiera. 
Personalización y coleccionables: 
● Desbloqueo de herramientas de evaluación y personalización de la oficina. 
● Reconocimientos como parte de los coleccionables. 
Elección de Game Engine 
Motor de juego seleccionado: Godot 
● Ligero y eficiente: Godot es un motor de juego ligero y de código abierto, 
ideal para proyectos 2D como "Fair Play". No requiere instalaciones pesadas 
y es fácil de configurar. 
● Soporte nativo para 2D: Godot tiene un sistema de renderizado 2D 
optimizado, perfecto para el estilo visual del juego, que se centra en sprites y 
interfaces. 
● Flexibilidad en el lenguaje de programación: Godot permite el uso de 
GDScript, un lenguaje similar a Python, que es fácil de aprender y usar para 
la lógica del juego. También soporta C# y C++ si se requiere mayor 
rendimiento. 
● Herramientas de UI integradas: Godot tiene un sistema de interfaz de 
usuario (UI) robusto y flexible, ideal para la interfaz minimalista y funcional 
que requiere el juego. 
● Comunidad y documentación: Aunque más pequeña que Unity, Godot tiene 
una comunidad activa y una documentación extensa, lo que facilita la 
resolución de problemas. 
● Gratuito: Al ser de código abierto, Godot no requiere pagos por licencias, lo 
que es ideal para proyectos independientes. 
Planeación (Diagrama de Gantt) 
 
 
 
 
 
Diagramas de alto nivel 
 
 
 
 
 
 
5. Herramientas de arte 
● Adobe Photoshop: Para la creación de sprites y texturas 2D. 
● Blender: Para la creación de objetos 3D (si se requieren). 
● Aseprite: Para la animación de sprites y creación de pixel art. 
● Godot Asset Library: Para la adquisición de assets adicionales como fondos, 
iconos y efectos visuales. 
6. Objetos 3D, Terreno y Escenas 
● Objetos 3D: Aunque el juego es principalmente 2D, se pueden utilizar objetos 
3D para elementos como la oficina del profesor o los muebles. 
● Terreno: No aplica, ya que el juego se desarrolla en interiores (aula, oficina). 
● Escenas: Las escenas se crearán en Godot utilizando nodos 2D para los 
fondos y objetos interactivos. Las escenas principales incluyen el aula, la 
oficina del profesor y el menú principal. 
7. Detección de colisiones, físicas e interacciones 
● Detección de colisiones: Godot tiene un sistema integrado de detección de 
colisiones 2D que se utilizará para las interacciones entre el cursor del 
jugador y los objetos interactivos (tareas, botones, etc.). 
● Físicas: No se requieren físicas complejas, ya que el juego no involucra 
movimiento dinámico de objetos. 
● Interacciones: Las interacciones se manejarán mediante scripts en GDScript 
que detectan clics del mouse y asignan acciones específicas (aprobar, 
rechazar, etc.). 
8. Lógica de juego e inteligencia artificial 
● Lógica de juego: La lógica principal se implementará en GDScript dentro de 
Godot. Esto incluye la revisión de tareas, la gestión financiera y la progresión 
del semestre. 
● IA de los estudiantes: Los estudiantes tendrán un comportamiento basado en 
probabilidades. Por ejemplo, un estudiante puede tener un 30% de 
probabilidad de usar IA de manera indebida, y esto aumentará con el tiempo. 
Audio y efectos visuales 
● Audio: Godot tiene un sistema de audio integrado que se utilizará para 
efectos de sonido y música ambiental. Los sonidos incluirán clics de botones, 
sonidos de papel y música relajante para la oficina. 
● Efectos visuales: Se crearán efectos simples en Godot, como resaltados al 
seleccionar tareas o animaciones de transición entre escenas. 
Plataforma y requerimientos de software 
Plataforma objetivo: PC 
Requerimientos mínimos: 
● Sistema operativo: Windows 10 (64-bit), macOS 10.12, o Linux (Ubuntu 
18.04) 
● Procesador: Intel Core i3 o equivalente 
● Memoria RAM: 4 GB 
● Tarjeta gráfica: Intel HD Graphics 4000 o equivalente 
● Almacenamiento: 2 GB de espacio disponible 
Requerimientos recomendados: 
● Sistema operativo: Windows 10 (64-bit), macOS 10.14, o Linux (Ubuntu 
20.04) 
● Procesador: Intel Core i5 o equivalente 
● Memoria RAM: 8 GB 
● Tarjeta gráfica: NVIDIA GTX 1050 o equivalente 
● Almacenamiento: 2 GB de espacio disponible
