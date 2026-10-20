# KartDash 🏎️ — Live Timing Delta PWA para Karting

App web progresiva (PWA) diseñada específicamente para montar en el **soporte del volante** de un kart de competición a más de 80 km/h.

🌐 **Enlace directo a la app**: [https://ktapp22.github.io/ENTRENAMIENTO/](https://ktapp22.github.io/ENTRENAMIENTO/)

---

## 🏁 Novedades de esta Versión

1. **Diseño 100% Horizontal (Landscape)**:
   - Bloqueo en apaisado para volante de kart.
   - Si se coloca en vertical, muestra aviso automático para girar el teléfono.
2. **Selector de Circuito**:
   - **Kartcenter Campillos (Málaga)** por defecto junto con su live timing directo.
   - Opción para otros circuitos de Apex Timing (Zuera, Lucas Guerrero, Karting Sevilla, o URL personalizada).
3. **Hero Delta en el Centro**:
   - Muestra en tamaño gigante (visible a alta velocidad con vibraciones) si vas **GANANDO TIEMPO (Verde)** o **PERDIENDO TIEMPO (Rojo)**.
   - Púrpura brillante cuando se bate el récord de vuelta personal (PB).
4. **Actualización Sector a Sector (S1, S2, Meta)**:
   - Al pasar por la antena del **Sector 1**, se registra el tiempo y el delta instantáneo.
   - Al pasar por el **Sector 2**, se calcula el delta acumulado.
   - Al cruzar la **Meta**, se cierra la vuelta y se compara con la mejor vuelta de la sesión.
5. **Sin distracciones**:
   - Eliminados los gaps con coches de delante y detrás.
   - Eliminado el listado de nombres de pilotos de la pantalla principal.
   - Solo telemetría pura: Posición, Vuelta, Delta Central y Cajas S1/S2/S3.
6. **Modo Test / Simulador en Volante**:
   - Permite probar el cambio de sectores, deltas y colores directamente en el volante antes de entrar en pista.

---

## 📱 Instalación en el Móvil (PWA)

1. Abre [https://ktapp22.github.io/ENTRENAMIENTO/](https://ktapp22.github.io/ENTRENAMIENTO/) en el navegador del móvil (Chrome en Android o Safari en iPhone).
2. Pulsa en **"Añadir a pantalla de inicio"** (o menú Compartir en iOS).
3. Se abrirá como app nativa a pantalla completa con pantalla siempre encendida (Wake Lock).
