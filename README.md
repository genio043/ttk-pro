# ttk-pro v1
TTK Calculator Pro: Calcula tiempo para matar con daño, regeneración, stats y gráfico interactivo. Hecho por un gamedev indie para otros gamedev.

# TTK Calculator Pro

Una herramienta avanzada para calcular el **Tiempo Para Matar (TTK)** en juegos, simulando daño, regeneración y más con un gráfico interactivo. Creada por un dev indie.

## Variables y su impacto

### Shooter
- **Precisión (%):** Porcentaje de disparos que aciertan (0-100). Baja precisión aumenta el TTK al reducir el daño efectivo.
- **Reducción Dispersión (%):** Reduce la dispersión del arma (0-100). Más reducción = mayor probabilidad de acertar, menor TTK.
- **Daño Boost (%):** Aumenta el daño base (0+). Más boost = más daño por disparo, menor TTK.
- **Fire Rate Boost (%):** Aumenta disparos por segundo (0+). Más boost = más disparos rápidos, menor TTK.
- **Reducción Recarga (%):** Reduce el tiempo de recarga (0-100). Más reducción = menos pausas, menor TTK sostenido.
- **Munición Boost (%):** Aumenta la capacidad del cargador (0+). Más munición = menos recargas, menor TTK en combates largos.

### Arma
- **Daño:** Daño por disparo (1+). Más daño = menor TTK.
- **Fire Rate:** Disparos por minuto (RPM) o segundo (RPS). Más rápido = más daño por segundo, menor TTK.
- **Dispersión (grados):** Ángulo de desvío de disparos (0+). Más dispersión = menos aciertos, mayor TTK.
- **Munición:** Balas por cargador (1+). Menos munición = más recargas, mayor TTK sostenido.
- **Tiempo Recarga (s):** Segundos para recargar (0+). Más tiempo = pausas largas, mayor TTK sostenido.

### Objetivo
- **Distancia (m):** Distancia al objetivo (0+). Más distancia = menos aciertos por dispersión, mayor TTK.
- **Ancho (m):** Ancho del objetivo (0+). Más ancho = más fácil acertar, menor TTK.
- **Alto (m):** Altura del objetivo (0+). Más alto = más fácil acertar, menor TTK.
- **Salud (HP):** Puntos de vida (1+). Más HP = más disparos necesarios, mayor TTK.
- **Armadura:** Puntos de armadura (0+). Absorbe daño, aumentando el TTK.
- **Absorción Armadura (%):** Porcentaje de daño absorbido por armadura (0-100). Más absorción = menos daño a HP, mayor TTK.
- **Regen Salud (HP/s):** Regeneración de HP por segundo (0+). Más regen = más daño necesario, mayor TTK o infinito.
- **Regen Armadura (/s):** Regeneración de armadura por segundo (0+). Más regen = más protección, mayor TTK.
- **Reducción Daño (%):** Reduce el daño recibido (0-100). Más reducción = menos daño efectivo, mayor TTK.

## Resultados
- **TTK (hasta 60s):** Tiempo simulado para matar (o "No mata" si HP > 0 a 60s).
- **TTK Teórico:** Tiempo exacto o "∞" si la regeneración supera el daño.
- **Stats:** Shots fired, reloads, accuracy, DPS (sustained/burst), daño total.

## Cómo usar los botones
1. **Calcular TTK:** Ingresa valores y haz clic para simular TTK, ver stats y gráfico (hasta 60s).
2. **Exportar JSON:** Guarda los valores y resultados en un archivo JSON.
3. **Resetear Datos:** Vuelve a valores predeterminados para empezar de nuevo.

## Uso
Ajusta las variables en los campos, selecciona RPM/RPS para fire rate, y presiona "Calcular TTK". Analiza el gráfico y stats para optimizar armas o enemigos en tus juegos.

---
Creado por un dev indie. ¿Útil? ¡Considéralo en [Buy me a Coffee](https://www.buymeacoffee.com/tuusuario)! Trabajos: Unity/WordPress, $25+.
