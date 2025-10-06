# Brainstorming y Desarrollo de la Aplicación de Movilidad

La aplicación permitirá a los usuarios ver buses, bicicletas y parkings cercanos, además de integrar una actividad social (seguidores, reviews, etc.) y mostrar disponibilidad de aparcamiento en tiempo real.

---

## 1. Dinámica de Brainstorming

### To Do (Problemas Detectados)
- Dificultad para encontrar transporte público cercano y en tiempo real.
- Falta de información sobre disponibilidad de bicicletas y parkings.
- Poca interacción social en aplicaciones de movilidad actuales.
- Usuarios no saben dónde hay sitio para aparcar sin dar vueltas.
- Integración de distintas fuentes de datos en una sola plataforma.
- Necesidad de una interfaz amigable y fácil de usar.
- Problemas de precisión en geolocalización y actualización de datos.
- Gestión de permisos y privacidad para uso de datos personales.

### In Progress (Posibles Soluciones)
- Uso de APIs de geolocalización para obtener ubicaciones exactas.
- Simulación de datos de transporte público con JSON si no hay API real.
- Incorporación de funciones sociales: seguidores, reviews, recomendaciones.
- Visualización en mapas interactivos con colores y símbolos claros.
- Alertas o notificaciones sobre disponibilidad de parkings o bicis.
- Diseño responsive para dispositivos móviles.
- Backend robusto para integrar varias fuentes de datos y sincronizarlas.
- Control de versiones y gestión de tareas para equipo de desarrollo.

### Done (Solución Seleccionada)
- Integración de Google Maps para geolocalización y visualización.
- API propia con datos simulados para transporte público.
- Sistema social básico: perfil, seguidores y reviews.
- Mapa interactivo mostrando buses, bicis y parkings con estado en tiempo real.
- Diseño simple, intuitivo y adaptado a móviles.
- Uso de GitHub para control de versiones y Trello para gestión del proyecto.

---

## 2. Diseño y Prototipado

### Usuarios Objetivo
- Personas que se mueven en zonas urbanas y usan transporte público.
- Usuarios de bicicletas compartidas.
- Conductores buscando aparcamiento.
- Usuarios interesados en movilidad sostenible y social.

### Pasos que Dará el Usuario
1. Abrir la app y permitir acceso a su ubicación.
2. Ver en el mapa opciones de buses, bicicletas y parkings cercanos.
3. Consultar disponibilidad en tiempo real.
4. Seguir a otros usuarios y leer/escribir reviews.
5. Recibir notificaciones sobre disponibilidad de aparcamiento.
6. Guardar lugares favoritos y rutas frecuentes.

### Prototipo Visual
<p align="center"><img width=800 alt="figma1" src="https://github.com/2DAMab/Hackathon1/blob/main/figma1.png"></p>
<p align="center"><img width=800 alt="figma2" src="https://github.com/2DAMab/Hackathon1/blob/main/Figma2.png"></p>
<p align="center"><img width=800 alt="figma3" src="https://github.com/2DAMab/Hackathon1/blob/main/Figma3.png"></p>
<p align="center"><img width=800 alt="figma4" src="https://github.com/2DAMab/Hackathon1/blob/main/Figma4.png"></p>
<p align="center"><img width=800 alt="figma5" src="https://github.com/2DAMab/Hackathon1/blob/main/Figma5.png"></p>

---

## 3. Tecnologías Seleccionadas

### Lenguajes de Programación
- **Frontend:** React native (permite desarrollar apps nativas para iOS y Android con una sola base de código, UI moderna y buen rendimiento).
- **Backend:** Java
- **Base de Datos:** MariaDB (relacional, robusta, con buen soporte).

### APIs
- **Geolocalización:** Google Maps API (precisión, funciones avanzadas y documentación amplia).
- **Transporte Público:** API simulada con JSON (en caso de no contar con datos reales).
- **Otras:** APIs para integración social si es necesario.

### Control de Versiones y Gestión
- **GitHub:** para control de versiones y colaboración.
- **Trello:** para gestión ágil de tareas y seguimiento del proyecto.

### Herramientas para Prototipado
- **Figma:** para prototipos visuales clicables y colaboración en equipo.

---
