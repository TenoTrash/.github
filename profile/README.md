## Meshtastic Argentina Community

Grupo dedicado a la información y ayuda cooperativa sobre la red Meshtastic https://meshtastic.org/ en Argentina.

### Unite a nuestro grupo de Telegram en https://t.me/meshtastic_argentina

---
### Canales activos (secundarios) en Meshtastic Argentina
| Canal | PSK | Región |
|--------|-----------|--------|
| BairesMesh | aB3K7ZIciBKq49nxn5gVmPQEtbTUVZOHKxuCaCKaHtA= | CABA & AMBA 
| RosarioMesh | kss+4MMhc9unauU8i6bix0Lt/pkjWMv1PIFr0fH8g58= | Rosario 
| NQNmesh | B7jYDJLWy9TSnajWI/yAJETLBcjN2RNXUU4jS4eRyJo= | Neuquén
| CordobaMesh |  CoRd0B4lHaBoN6OWT0u2EvNX9Jci7gsIiIJtD30BCCw= | Córdoba

### ¡ Como primario estamos utilizando LongFast !

---
## Equipamiento mínimo para armar un nodo portátil Meshtastic

Opciones de placas recomendadas:

- **HelTec T114 (v2) **  👉 [Tienda Starware](https://tienda.starware.com.ar/producto/placa-desarrollo-lora-bt-gps-heltec-mesh-node-t114-nrf52840sx1262-v20-pantalla/) Viene con Bluetooth y pantalla. Ideal para empezar.

- **HelTec T114 (v2) kit con GPS **
  👉 [Tienda Starware](https://tienda.starware.com.ar/producto/kit-desarrollo-lora-bt-gps-heltec-antena-mesh-node-t114-nrf52840sx1262-v2/)
  Viene con Bluetooth, GPS y pantalla. Ideal para empezar.

- ** HELTEC LORA32 V3 (kit con gabinete) **
  👉 [Tienda Starware](https://tienda.starware.com.ar/producto/placa-desarrollo-iot-lora-heltec-lora32-v3-node-sx1262-esp32-s3-868-928mhz/)
  Viene con Bluetooth y WiFi. Simple y clásico. Consume bastante energía más energía que el T114 y ya no es recomendable para nodos portátiles a batería.

⚠️ **Importante:** Si comprás en otro lado, asegurate de que la frecuencia sea **915 MHz** (o un número cercano).  
⚠️ **Cuidado con la versión de HelTec:** buscá que sea **v3** o **T114 v2**.

---
Software y configuración:

- **Flasheo del firmware:**  
  👉 [https://flasher.meshtastic.org/](https://flasher.meshtastic.org/)

- **App oficial para Android:**  
  👉 [Google Play](https://play.google.com/store/apps/details?id=com.geeksville.mesh&hl=es&pli=1)

- **Región de radio:**  
  Configurá la región como **ANZ**.
  Esto asegura compatibilidad con la red local y el canal público llamado **LongFast** es el que usamos como canal de encuentro base. Desde ahí podés elegir tu nombre de usuario y conectarte sin complicaciones.
  Con esta configuración básica, si hay en las cercanías otros nodos, van a ir apareciendo en el listado de la app. Si no ves ninguno, puede ser que no haya nadie cerca. Como todo equipo de radio, depende de la altura, el despeje y la distancia con el resto de los integrantes de la malla.

  📎 ANZ es la región adoptada oficialmente en Argentina para operar en frecuencias libres:  
  👉 [Resolución ENACOM 581/2018 – AU915-928](https://www.enacom.gob.ar/multimedia/normativas/2018/res581MM.pdf)

- **Zona horaria para Argentina:**  
  Al configurar el equipo, en el menú Device, ingresá **ART3** en la POSIX Timezone para que salga la hora correcta en pantalla.

---
A group dedicated to provide information and cooperative assistance about the topic of the Meshtastic network https://meshtastic.org/ in Argentina.

Join us at Telegram https://t.me/meshtastic_argentina

---
Meshtastic® is a registered trademark of Meshtastic LLC. Meshtastic software components are released under various licenses, see GitHub for details. No warranty is provided - use at your own risk.
