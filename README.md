# Supervivencia Zombi — Three.js

## Ejecutar
1. Descomprime `t3_proyecto.zip`.
2. Abre la carpeta `t3_proyecto` en VS Code.
3. Ejecuta `index.html` con la extensión **Live Server** (recomendado).
   También puedes iniciar un servidor local desde la carpeta `t3_proyecto` con `python -m http.server 8000`
   y abrir `http://localhost:8000`.

No abras el archivo directamente con `file://`: los módulos ES y la carga de `models/maxwell.glb`
necesitan un servidor local.

## Controles
- **A | D | W | S**: Izquierda| Derecha | Avanzar | Retroceder.
- **1 y 2**: Cambiar arma, Pistola y Rifle 

## Archivos
- `index.html`: página, interfaz y estilos.
- `main.js`: escena Three.js, personajes 3d, obstáculos, animación y reglas del juego.
- `models/headcrab_zombie.glb`: modelo 3D del personaje de Half-Life 2.
- `models/pistola.glb`: Modelo 3D de la pistola.
- `models/rifle_ak47.glb`: Modelo 3D del rifle AK-47
- `models/helicoptero:.glb`: Modelo 3D del Helicoptero Huey.
- `textures/`: texturas del proyecto.
