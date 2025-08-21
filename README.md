 Sistema de Alimentación Automática para Ganado AgrooFeed
🎯 Objetivo

El objetivo del proyecto es automatizar el proceso de distribución de alimento para el ganado (vacunos, cerdos u otros animales de granja), garantizando que reciban la cantidad adecuada en los horarios programados, sin necesidad de intervención manual. Con esta solución se busca optimizar el tiempo de los encargados, reducir errores en la entrega de raciones y asegurar un control más eficiente del consumo de alimento.

🐄 ¿Para qué sirve?

El sistema está diseñado para:

Alimentar automáticamente a los animales en horarios establecidos.

Controlar la cantidad de comida distribuida, evitando exceso o déficit.

Monitorear el nivel de alimento en la tolva y alertar cuando sea necesario reabastecer.

Generar reportes de consumo para llevar un control de la alimentación diaria.

Reducir la carga laboral de los trabajadores de la granja y mejorar la eficiencia en la producción.

🛠️ Componentes a Utilizar

Unidad de Control

Arduino UNO / Nano o ESP32 (para integración Wi-Fi).

RTC (Real Time Clock) para la gestión de horarios de alimentación.

Mecánica y Actuadores

Motor DC o motor paso a paso → acciona el tornillo sin fin o compuerta.

Servomotor → regula la apertura y cierre del dispensador.

Relé → control de motores de mayor potencia.

Sensores

Sensor de peso (célula de carga + HX711) → mide la cantidad de comida servida.

Sensor de nivel (ultrasónico o infrarrojo) → detecta alimento disponible en la tolva.

Interfaz Local

Pantalla LCD 16x2 o indicadores LED → muestran el estado del sistema.

Botones → permiten programación manual de horarios y raciones.

Conectividad y Monitoreo (opcional)

ESP32/ESP8266 → conexión a Wi-Fi para control remoto.

Raspberry Pi → dashboard con Node-RED, base de datos (MySQL o SQLite) y registro de alimentación.

Notificaciones vía Telegram Bot o correo electrónico en caso de fallas.
