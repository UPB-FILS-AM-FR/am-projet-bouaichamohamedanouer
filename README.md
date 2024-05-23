# Station meteo

| | |
|-|-|
|`Author` | Mohamed Anouer Bouaicha

## Description
Station météo qui mesure la température, l'humidite, la pression et l'affiche sur un écran.
## Motivation
j'aime  la météo et je souhaite disposer d'une station météo pour suivre les conditions météorologiques locales.
## Architecture
La station météo est composée de trois composants principaux :

Un thermomètre qui mesure la température ambiante.
Un écran qui affiche la température mesurée par le thermomètre.
Un capteur de pression barometrique qui mesure la pression ambiante
Le thermomètre et le capteur de pression sont connecté à un Arduino, qui est un microcontrôleur. L'Arduino reçoit les données les affiche sur l'écran.
### Block diagram

<!-- Make sure the path to the picture is correct -->
![Block Diagram](meteo.png)

### Schematic

![Schematic](Schema.png)

### Components

<!-- This is just an example, fill in with your actual components -->

| Device | Usage | Price |
|--------|--------|-------|
| Arduino  | Plaque de base  | [25 RON](https://www.optimusdigital.ro/ro/compatibile-cu-arduino-nano/1686-placa-de-dezvoltare-compatibila-cu-arduino-nano-atmega328p-i-ch340.html?search_query=Arduino+Nano&results=22) |
| termometre  | detecte la temperature | [7 RON](https://www.optimusdigital.ro/ro/senzori-senzori-de-temperatura/584-senzor-de-temperatura-dht11.html?search_query=dht11&results=17) |
| capteur pression | detecte la pression | [9 RON](https://www.optimusdigital.ro/ro/senzori-senzori-de-presiune/1777-modul-senzor-de-presiune-barometric-bmp280.html?search_query=senzor+presiune+barometrica&results=4) |
| Ecran | Affiche | [17 RON](https://www.optimusdigital.ro/ro/optoelectronice-lcd-uri/2894-lcd-cu-interfata-i2c-si-backlight-albastru.html) |
| Jumper Wires | Connecting components | [7 RON](https://www.optimusdigital.ro/ro/fire-fire-mufate/884-set-fire-tata-tata-40p-10-cm.html?search_query=set+fire&results=110) |
| Breadboard | Project board | [10 RON](https://www.optimusdigital.ro/ro/prototipare-breadboard-uri/8-breadboard-830-points.html?search_query=breadboard&results=145) |


### Libraries

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| [pour l'ecran](https://github.com/blackhack/LCD_I2C/blob/master/src/LCD_I2C.h) | Arduino library to control a 16x2 LCD via an I2C adapter based on PCF8574| Pour pouvoir utiliser l'ecran LCD  |
| [pour la temperature](https://github.com/adafruit/DHT-sensor-library) | An Arduino library for the DHT series of low-cost temperature/humidity sensors. | Pour pouvoir utiliser le dht11  |
| [pour la pression](https://github.com/adafruit/Adafruit_BMP280_Library) | An Arduino library for the DHT series of low-cost temperature/humidity sensors. | Pour pouvoir utiliser le bmp280   |

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May

### Week 7 - 19 May

### Week 20 - 26 May


## Reference links

<!-- Fill in with appropriate links and link titles -->

[Tutorial 1](https://www.youtube.com/watch?v=wdgULBpRoXk&t=1s&ab_channel=BenEater)

[Article 1](https://www.explainthatstuff.com/induction-motors.html)

[Link title](https://projecthub.arduino.cc/)
