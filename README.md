# -Sof-5D-XR-Wellness
## Resumen
Sofá inteligente reclinable que combina experiencias multisensoriales 5D, Realidad Virtual (VR) y Realidad Aumentada (AR), equipado con brazos robóticos de masaje y sensores para monitorear los signos vitales del usuario. Diseñado para wellness, entretenimiento y aplicaciones terapéuticas.

---

## Objetivos del Proyecto

- Ofrecer experiencias inmersivas y personalizadas de relajación y bienestar.
- Medir y mostrar en tiempo real los signos vitales del usuario.
- Sincronizar efectos físicos (vibración, calor, aromas, masaje, etc) con experiencias XR.
- Permitir control total mediante pantalla táctil, aplicación móvil y comandos por voz.

---

## Componentes Principales

1. **Sofá Reclinable Inteligente**
   - Estructura ergonómica, tapizado premium (ver imagen 1).
   - Brazos robóticos con varios grados de libertad para masaje personalizado.
   - Compartimentos para electrónica y actuadores.

2. **Sistema Multisensorial 5D**
   - Motores de vibración e inclinación.
   - Emisores de aromas y/o ventiladores para viento.
   - Iluminación ambiental (LED RGB).
   - Módulos de calor localizados.

3. **Sensores Biométricos**
   - Frecuencia cardíaca (PPG/ECG).
   - Oxigenación (pulsioxímetro).
   - Temperatura corporal.
   - Presión arterial.
   - Sensor de respiración.

4. **Módulo XR (VR/AR)**
   - Visor/Headset VR (Oculus, PlayStation VR, compatible).
   - Soporte para AR: visualización de datos sobrepuestos en la experiencia virtual.
   - Sincronización con el software del sofá y sensores.

5. **Electrónica y Control**
   - Microcontrolador central (Raspberry Pi, ESP32, Arduino, etc).
   - Módulos de comunicación (Bluetooth, WiFi).
   - Integración IoT para registro y acceso remoto.

6. **Interfaz de Usuario**
   - Pantalla táctil integrada y/o app móvil.
   - Control por voz (Alexa, Google Assistant).
   - Feedback visual de signos vitales y configuración de experiencia.

---

## Arquitectura Básica del Sistema

```
[Usuario]
   |
[Sofá Inteligente] -- [Brazos de masaje]
   |          |
[Sensores]   [Sistema 5D]    [XR Headset]
   |          |                  |
[Microcontrolador central] <--- [Interfaz de usuario: Pantalla/App/Voz]
   |
[Nube/Servidor IoT (opcional)]
```

---

## Escenario de Uso

1. El usuario se sienta, el sofá detecta la presencia y ajusta postura.
2. El usuario selecciona una experiencia (relajación, meditación, juego, etc.) en la pantalla o app.
3. Se coloca el visor XR; inicia la experiencia multisensorial.
4. Los brazos de masaje y los efectos 5D se sincronizan con el entorno virtual.
5. El sistema mide los signos vitales y los muestra en tiempo real en AR o en la app.
6. Al finalizar, el usuario recibe recomendaciones personalizadas según sus datos biométricos.

---

## Siguientes pasos sugeridos
- Especificación de componentes y materiales (BOM).
- Diseño de diagramas eléctricos y mecánicos.
- Desarrollo del software de integración y control.
- Prototipado rápido y pruebas con usuarios.

---
