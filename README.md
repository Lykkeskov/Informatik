16/08/24
opg. 1: logbog:
  - nyt projekt på github
  - README: 1. Forløb - Tello dronen


opg. 2: analyse af Tello dronen som itsystem ift. 3-lags modellen:

Selve dronen
  - Præsentationslag:
    Sensoren bruges til at se omgivelserne.
  - Logiklag:
    Dronen udfører de aktioner, som den har fra datalaget.
  - Datalag:
    Sensorer, wifi, batterisensor, kamera, akcelerationsmeter, geometer
    Dronen modtager data fra appen i form af kode/de kommandoer, som brugeren har givet som input.

App
  - Præsentationslag:
    Brugeren anvender dronens app eller skriver selv kode, der får dronen til at udføre forskellige aktioner.
  - Logiklag:
    Appen går igennem den data/kode/de kommandoer, som den har fået af brugeren og sender dem til dronen.
  - Datalag:
    De kommandoer som den har fået af brugeren.

Resume af dagen:
I dag har vi lært at bruge en Tello drone. Vi har lært at skrive kode i pycharm, og sende kommandoer til dronen via dens wifi.



26/08/2024
Vi startede med at lære lidt om arduino og innovation (med 4p modellen: https://www.google.com/url?sa=i&url=https%3A%2F%2Fcloud.cct.au.dk%2Fwiki%2Findex.php%3Ftitle%3DInnovation&psig=AOvVaw0PzBB5K49oDxGKkv3aSFuH&ust=1724751968398000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCND4y_avkogDFQAAAAAdAAAAABAE).


Innovation (4P)
- Idégenerering til projekt dronecontroller
    BRAINSTORM - vores idéer:
    - Mind control
    - playstation 4 controller / joystick (m. laser)
    - Forsøgelsesdrone m. laser
    - grap ting og drop ting
    - Drone som følger efter person. evt. gør brug af motionsensor el. lyspunkt el. kode ting

Vi har valgt at arbejde med, at lave noget, der gør at en drone kan følge efter en.



12/09/2024

Arduino sender data til oc i form af 0/1
Den slukker og sender: TX (transmit) og RX (recieve)
baudrate: changes per second (hos arduino 115200)

Protokol: 
 - data: acc.x m/s
 - arduino: ____
 - pc/python: float

