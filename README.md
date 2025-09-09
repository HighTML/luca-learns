# Luca Learns - Dutch Tech Tutorials

> Collection of self-written and curated tech tutorials for my son Luca, covering Python, micro:bit, Arduino, ESP32, Raspberry Pi, and what not. The language used will mainly be Dutch, with some English added in.

## Python op de BBC Micro:Bit

### Hardware en software

#### Hardware 

Een computer of microcontroller (het verschil leren we zo!) is opgebouwd uit *hardware*. Hardware is alles wat je aan kan raken, de chips, schakelaars en electrische componentjes in het apparaat. Je kan de hardware in een computer of microcontroller onderverdelen in:
* **Input** - onderdelen waarmee het apparaat informatie krijgt van de buitenwereld. Voorbeelden: toetsenbord, muis, joystick, schakelaar, temperatuur sensor, touchscreen (die raak je aan = input)
* **Output** - onderdelen die iets laten zien of doen voor de gebruiker. Voorbeelden: scherm (display), LED lampjes, motoren, speakers, buzzers.
* **Werkgeheugen** - tijdelijk geheugen waar programma’s gegevens bewaren en bewerken terwijl ze draaien.
  Wordt vaak _RAM_ genoemd. Als je bijvoorbeeld programmeert `getal = 5` dan komt `getal` in je werkgeheugen te staan.
* **Permanente opslag** - geheugen dat alles onthoud als je het apparaat uitzet.
  Voorbeelden: USB stick, microSD kaart, harde schijf.
* **Centrale Processor** - (CPU of _Central Processing Unit_) – de master chef die alle opdrachten uitvoert en de andere onderdelen aanstuurt.
* **Klok / timer** – zorgt dat alles op het juiste moment gebeurt.
* **Verbindingsbussen** – een systeem van elektrische draden of lijnen in een computer of microcontroller dat onderdelen met elkaar laat communiceren, de “wegen” waarlangs informatie tussen alle onderdelen reist. Zo kan de CPU lezen en schrijven naar het geheugen of RAM, of kan je `pin 0` uitlezen.
* **Randapparatuur** – extra onderdelen die je erop aansluit om meer dingen te kunnen doen.
  Voorbeelden: WiFi modules, USB apparaten, printers, extra sensoren of extra displays. Randapparatuur kan zowel voor input of output zijn. 

#### Software

Software is alles wat je niet kunt aanraken, maar wat op de hardware draait om iets te laten gebeuren.
Software zijn programma’s en instructies die de computer of microcontroller vertellen wat hij moet doen. Zonder software doet de hardware niets nuttigs. Je doet het apparaat aan en er gebeurd niks. 

Sommige apparaten hebben software die niet veranderd kan worden. Denk aan een moderne magnetron met een mooie display. In de fabriek is er een programma op gezet en dat kan niet gewijzigd worden. 

Software kan ook wijzigbaar zijn, zoals programma’s die je zelf schrijft in Python of andere programmeertalen. Op microcontrollers zoals de `micro:bit` zet je code die de hardware laat werken, bijvoorbeeld lampjes laten knipperen of sensoren uitlezen. 



### Het verschil tussen microcontroller en computer

We gaan Python leren door de `micro:bit` te programmeren. De `micro:bit` is een _microcontroller_. Een microcontroller is eigenlijk geen computer! Op een microcontroller kan maar één programma tegelijk draaien. Op een echte computer kunnen heel veel programma's tegelijk draaien. Dat komt omdat op een echte computer een OS of *Operating System* is geïnstalleerd. Als een computer opstart wordt eerst het OS ingeladen en opgestart. Dat duurt altijd even, daarom start een laptop of een iPad niet meteen op. Pas als het OS is opgestart kan het OS zelf andere programma's opstarten. Zoals bijvoorbeeld de Desktop op een Macbook. Een aantal bekende OSen zijn MacOS, Windows, Linux, Raspberry OS. Er kunnen op een computer meerdere programma's (meerdere software) tegelijk draaien.

Een microcontroller is eigenlijk geen computer, en micro controller kan maar één programma tegelijk draaien maar dat doet hij wel heel goed! 

Hoe zit dat? Een CPU kan eigenlijk maar 1 ding tegelijk doen. Ergens is een programma of een proces dat tegen de CPU zegt "bereken voor mij `3*8/2`". Terwijl de CPU dat doet kan hij niks anders doen. 

Bij een computer geeft het Operating Systeem (OS) verschillende programma's omstebeurt eventjes tijd om iets aan de CPU te vragen. Het OS geeft dus de CPU beurt om en om aan bijvoorbeeld je browser, je desktop, je Finder, dan je muis, en dan begint het weer opnieuw bij de browser. Zo lijkt het alsof alles tegelijk werkt, maar eigenlijk is het steeds omstebeurt. Het kan wel eens gebeuren dat 1 programma een fout heeft en dat daardoor niks meer werkt. Het OS is aan het wachten tot dat ene programma de beurt weer terug geeft maar dat gebeurt niet. Dan "hangt" de computer en moet je hem even uit- en aanzetten. 

Bij een microcontroller is geen OS, dus er is maar 1 programma dat draait: jouw eigen programma! Je hebt dus veel minder geheugen nodig, en er is een simpelere CPU nodig omdat er geen OS hoeft te draaien. Daarom zijn microcontrollers veel goedkoper! Je hebt al microcontrollers voor een paar euro! 

#### Microcontroller hardware
Enkele voorbeelden van microcontrollers zijn:
* Micro:bit
* Arduino
* M5Stack en M5Stick
* Raspberry Pi Pico 

> _Wij hebben thuis de micro:bit, enkele Arduino's, M5Stack en M5Stick._

#### Computer hardware
Enkele voorbeelden van computers zijn:
* Macbook
* Windows laptop
* Raspberry Pi 1, 2, 3, 4, 5
* Raspberry Pi Zero 

> _Wij hebben thuis Macbooks, Raspberry Pi 3 en Zero._