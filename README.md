# Actividad-Guia-5-Fase-2
# 1. Exploración del Problema — Definición del MVP
Analizamos el caso de Repartos Rápidos SAS y los problemas concretos que tiene: operación manual, sin trazabilidad para el cliente y sin forma de escalar. Con eso en mente, definimos cuatro funcionalidades que tienen que estar sí o sí en la primera entrega para que el sistema sea útil:<img width="722" height="287" alt="image" src="https://github.com/user-attachments/assets/037a631c-1ab4-48f1-a579-c846cb0f5924" />

# 2. Diseño de la Experiencia — Wireframes
Bocetos de las tres pamntallas principales del MVP, en la cual se prioriza la claridad en el flujo antes que el diseño visual
# Pantalla 1 Formulario de registro de un envio nuevo (Panel Administrador)
<img width="723" height="465" alt="image" src="https://github.com/user-attachments/assets/a8c30c50-099d-4ff3-a72a-8e937e84a683" />

# Pantalla 2 Dashboard del administrador
<img width="725" height="398" alt="image" src="https://github.com/user-attachments/assets/19493ddd-51e5-41f3-a3f7-8ec673e8babe" />

# Pantalla 3 Pagina publica de rastreo (Cientes)
<img width="725" height="352" alt="image" src="https://github.com/user-attachments/assets/cc8eb6e3-c1a3-4b69-bd71-07c7e59c055d" />

# 3. Diseño de Arquitectura y Planificación
Aqui podemos analisar que la arquitectura seria tres capas, el frontend no se comunica directamente con la base de datos, primero pasa por la API REST, que actua como intermediario y aplica la logina de negocio.
<img width="724" height="179" alt="image" src="https://github.com/user-attachments/assets/8f2d5168-000d-4ba3-8a87-7decdf7fe50c" />

# Estructura JSON Modelamiento de datos
El sistema maneja dos entidades principales: Paquete y repartidor, cada paquete almacena los datos del remitente, destinatario, dimensiones fisicas, estado actual del envio y repartidor asignado. El repartidor, por su parte registra su ubicacion geografica en tiempo real y la lista de paquetes que tiene a su cargo.
Los estados posibles de un paquete son: En bodega, en ruta, entregrado e incidencia.
<img width="725" height="168" alt="image" src="https://github.com/user-attachments/assets/c637d404-7114-4785-a8ca-262a9dcc3704" />

# Planificacion de tareas para el proeycto en GitHub Projects
Las tareas de esta primera fase estan organizadas en tres frentes: base de datos, backend y frontend. El objetivo es tener un MVP funcional con registro de paquetes, gestión de estados y rastreo público por número de guía. El mapa de ubicación en tiempo real de la flota queda pendiente para la Fase 2.
Las tareas se gestionan en GitHub.
<img width="579" height="487" alt="image" src="https://github.com/user-attachments/assets/70f443f6-ad14-4e62-a87f-aef25563b399" />






