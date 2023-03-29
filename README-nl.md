| Repository Status | ESPHome S0tool discord Community |
| :--- | :--- |
| [![last commit time][github-last-commit]][github-master] [![GitHub Activity][commits-shield]][commits] | [![Discord][discord-shield]][discord] ![Twitter Follow](https://img.shields.io/twitter/follow/huizebruin?style=social) 
|  [![License][license-shield]](LICENSE) [![Forks][forks-shield]][forks-url] [![Stargazers][stars-shield]][stars-url] [![Issues][issues-shield]][issues-url] | [![Contributors][contributors-shield]][contributors-url] [![GitHub release](https://img.shields.io/github/release/huizebruin/s0tool.svg)](https://GitHub.com/huizebruin/s0tool/releases/)| 


|  S0tool | Made for ESPHome program |
| :--- | :--- |
|  ![S0tool-logo](./static/assets/s0tool-logo.jpg)  | ![ESPHome](./static/assets/made-for-esphome-black-on-white.png) |


|  S0tool | Dashboard  |
| :--- | :--- |
|  ![S0tool-print](./static/assets/s0tool-huizebruin.jpg)  | ![dashboard](./static/assets/s0tool-dashboard.png) |


 
<br><br>
# De <b>S0tool</b> bestellen?
[https://www.huizebruin.nl/shop](https://www.huizebruin.nl/shop)</br>
Op dit moment verzenden we alleen naar : Nederland en België. 

## Als je hem zelf wilt bouwen.
Dan heb je de volgende onderdelen nodig<br>
en plaats een weerstand tussen D2 en de  5V.

Wemos D1 mini ep8266 [Aliexpres](https://s.click.aliexpress.com/e/_9fhHxf) of [Amazon](https://amzn.to/3FL7O48) of bij de Nederlandse webshop  [Opencircuit](https://opencircuit.nl/Product/WeMos-D1-mini-V3.1-Wifi-Module?affiliate=1VL4KIAMBZ&cid=github)<br>

Npn Sensor [Aliexpres](https://s.click.aliexpress.com/e/_AVaoGr) of [Amazon](https://amzn.to/3DFVsaL) of bij de Nederlandse webshop  [Opencircuit](https://opencircuit.nl/product/lj18a3-8-z-bx-5v-nabijheids-sensor-n-o-npn-8mm?affiliate=1VL4KIAMBZ&cid=github)<br>

10K weerstand [Aliexpres](https://s.click.aliexpress.com/e/_A10BHz) of [Amazon](https://amzn.to/3NBjjx2) of bij de Nederlandse webshop [Opencircuit](https://opencircuit.nl/Product/10K%CE%A9-Metaalfilm-weerstand-1-4W-10-stuks?affiliate=1VL4KIAMBZ&cid=github)<br>

En een usb kabel en een usb lader van minimaal 5v and 1A.

![S0tool-diy](./static/assets/npn-watermeter-wemosd1.png)

Werkt dit met mijn meter kijk dan hier. https://github.com/huizebruin/s0tool/discussions/57<br>


Voor meer informatie en aansluitschema's etc kijk dan even op de [website](https://www.huizebruin.nl/home-assistant/wat-is-de-s0tool/).
# Update:
| Datum | Informatie |
| :--- | :--- |
| 05/05/2022 | V2 is binnen maar moet nog getest worden.|
| 06/05/2022 | Nu ook mogelijk om de <b>s0tool</b> direct via de browser te flashen. [https://huizebruin.github.io/s0tool/](https://huizebruin.github.io/s0tool/)
| 25/07/2022 | Watermeter geeft nu liter per minuut aan met vertraging van 2 seconden.|
| 04/08/2022 | Tekst vertaald op Github naar [English](./README.md) en [Dutch](./README-nl.md).|
| 10/09/2022 | Flash pagina geüpdatet nu keuzemogelijkheden --> standaard / watermeter / 1000imp puls / 2000imp puls .|
| 29/10/2022 | Fix om de watermeter sensor toe te voegen aan het energy dashboard.|
| 12/11/2022 | Fix voor de watermeter total and watermeter meter counter numbers.|
| 14/11/2022 | Fix voor de watermeter werkt nu met 2 pulses per liter kies 0.0005  en 1 puls per liter kies 0.001 default is 0.001.|
| 18/11/2022 | Fix voor meter teller van de kWh en water, en wat opruimen van de code.|

<br>
Voordat je de S0tool gaat updaten zorg ervoor dat je minimaal het onderstaande draait.

| Program | version |
| :------------- | :--------- |
| Home Assistant | v2022.11.1 |
| ESPHome | v2022.10.1 |

<br>

***
<br>

### Software update informatie zie de [releases](https://github.com/huizebruin/s0tool/releases) sectie op github.
***

# Hardware
Vul eerst uw  🛒 of kijk of je de onderstaande componenten al hebt .
#
## Voeding
- Minimaal 5v 1A [Bol.com](https://partner.bol.com/click/click?p=2&t=url&s=1097464&f=TXL&url=https%3A%2F%2Fwww.bol.com%2Fnl%2Fnl%2Fp%2Funiversal-usb-adapter-usb-stekker-usb-lader-blokje-universeel-zwart%2F9300000030638594%2F&name=Universal%20USB%20adapter%20-%20USB%20stekker%20-%20USB%20lader) 
- usb kabel [Bol.com](https://partner.bol.com/click/click?p=2&t=url&s=1097464&f=TXL&url=https%3A%2F%2Fwww.bol.com%2Fnl%2Fnl%2Fp%2Fzware-kwaliteit-0-3-m-usb-oplaadkabel-oplaadsnoer-kabel-voor-snelladen-past-ook-op-huawei-ascend-3-ideos-x3-mate-10-lite-mate-8-mate-s-p-smart-p10-lite-p8-lite%2F9200000124489693%2F&name=Zware%20kwaliteit%200%2C3%20m%20USB%20oplaadkabel.%20) of [opencircuit.nl](https://opencircuit.nl/product/Micro-USB-kabel-100cm-blauw-30AWG?affiliate=1VL4KIAMBZ)

Of een alles in 1 lader met snoer [Opencircuit.nl](https://opencircuit.nl/product/5V-2.5A-Adapter-Micro-USB-B-Raspberry-Pi?affiliate=1VL4KIAMBZ&cid=github) of bij [Bol.com](https://partner.bol.com/click/click?p=2&t=url&s=1097464&f=TXL&url=https%3A%2F%2Fwww.bol.com%2Fnl%2Fnl%2Fp%2Fxssive-usb-lader-met-micro-usb-kabel-voor-motorola-smartphones-o-a-moto-x-moto-g-moto-e-nexus-6%2F9200000055360796%2F&name=Xssive%20USB%20Lader%20met%20Micro%20USB%20Kabel%20).
#
## Voor de watermeter
- NPN sensor - [Aliexpress](https://s.click.aliexpress.com/e/_AaxBxa) of [Aliexpress](https://s.click.aliexpress.com/e/_ADG3ri) of [Aliexpress](https://s.click.aliexpress.com/e/_A4Lsko) of in Nederland bij [Opencircuit.nl](https://opencircuit.nl/product/lj18a3-8-z-bx-5v-nabijheids-sensor-n-o-npn-8mm?affiliate=1VL4KIAMBZ&cid=github)
- (Zorg ervoor dat het sensoren voor 5V zijn niet 6V of hoger!!) Ik gebruik zelf de LJ18A3-8-Z/BX-5V <br> ![afbeelding](./static/assets/water-npn.png)<br>

NPN sensor naar de S0tool<br>
![watermeteraansluiting](./static/assets/s0tool-watermeter.jpg)<br>

Cyble sensor V2 naar de S0tool<br>
![watermeteraansluiting](./static/assets/s0tool-cyble-sensor-v2.jpg)<br>
Hier moet u een weerstand van 10k Ohm toevoegen tussen de GND en D2

## Watermeter op het energy dashboard.
Vanaf Home Assistant versie 2022.11.X is het mogelijk om met de S0tool vanaf versie v22.10.20 de watermeter toe te voegen aan het energie dashboard. <br>
|  Enegry dashboard | Dashboard  |
| :--- | :--- |
|  ![S0tool-water-energy-dashboard](./static/assets/water-energydashboard.jpg)  | ![dashboard](./static/assets/s0tool-dashboard.jpg) |

***
Binnenkort ook de sensor voor de Elster V100 kogelvorm meter te bestellen welke ook werkt met de S0tool houd de shop in de gaten.

Voor meer informatie en aansluitschema's etc kijk dan even op de [website](https://www.huizebruin.nl/home-assistant/wat-is-de-s0tool/).

***
## Voor het bijhouden van zonnepanelen of warmtepomp etc.
- 45A kWh meter met 1000 pulses per kWh [Bol.com](https://partner.bol.com/click/click?p=2&t=url&s=1097464&f=TXL&url=https%3A%2F%2Fwww.bol.com%2Fnl%2Fnl%2Fp%2Fsdm120d-mid-1-fase-kwh-meter-met-puls-uitgang%2F9200000112029366%2F&name=SDM120D%20MID%20-%201%20Fase%20kWh%20meter%20met%20puls%20uitgang)
- 40A kWh meter met 2000 pulses per kWh [Bol.com](https://partner.bol.com/click/click?p=2&t=url&s=1097464&f=TXL&url=https%3A%2F%2Fwww.bol.com%2Fnl%2Fnl%2Fp%2Felektronische-wattmeter-greenblue-gb173-voor-zowel-prive-als-handel-industrie%2F9200000115897616%2F&name=Elektronische%20wattmeter%20GreenBlue%20GB173) <br>
- 32A kWh meter met 2000 pulses per kWh [Amazon](https://amzn.to/3P6CSg0)
- 40A kWh meter met 1000 pulses per kWh [Amazon](https://amzn.to/3oV08ms)

Worden er 2000 pulsen per kWh gegeven. Dit wil dus zeggen dat elke plus een waarde van 1/2000 = 0.0005 kWh
Worden er 1000 pulsen per kWh gegeven. Dit wil dus zeggen dat elke plus een waarde van 1/1000 = 0.001 kWh

2000 imp/kWh : geeft 2.000 impulsen per kWh. is dus nauwkeuriger om een meting te doen dan de 1000 imp/KWh
Hoe meer energie u verbruikt of terug levert, des te sneller zal hij gaan schakelen.<br>


![afbeelding](./static/assets/kwh-s0.png)<br>
#
## De s0 aansluiting <br>
![afbeelding](./static/assets/kwh_Meter_Pulse.jpg)<br>
Hoe de S0 kWh meter te verbinden met de S0tool<br>
![afbeelding](./static/assets/s0tool-s0-kwh-poort.jpg)<br>
In <b>v1</b> zit een klein foutje, in de s0 aansluiting zit de<b>GND</b> I.P.V <b>5v+</b>.<br>
Dat werkt niet,  dit is een ontwerpfoutje. <br>
Er moet dus een kabeltje vanaf de 5v+ op het printje naar poort 20 op je kWh meter.<br>
En het andere kabeltje gaat vanaf de D5 aansluiting op het printje naar poort 21 op de kWh meter.
<br> Sinds 01-07-2022 wordt alleen nog maar V2 verstuurd.
***
<br>
## Informatie:<br>
  Wi-fi : IEEE 802.11 b/g/n 2.4GHz 

  <br><br>
## Installatie: 

Eerst dien je de CH340 drivers te installeren.
De drivers ch340 kan je hier vinden. 
[https://sparks.gogo.co.nz/ch340.html](https://sparks.gogo.co.nz/ch340.html) <br>

06/05/2022: <br> Nu ook mogelijk om de <b>s0tool</b> direct via de browser te flashen.<br>
Alleen mogelijk met een chrome of edge en opera browser. <br>
Verbind de s0tool met een usb kabel aan je pc/ laptop en start de procedure.
 [https://huizebruin.github.io/s0tool/](https://huizebruin.github.io/s0tool/)

1. Installeer Home Assistant & Esphome .
2. Connect de wemos d1 mini aan een usblader.
3. Ga met je laptop of telefoon naar     <b>ssid:</b> ```S0tool``` 
4. Ga naar ```192.168.4.1```.
5. Zet de juiste SSID en Wachtwoord in de velden
6. Wacht tot hij klaar is, en dan geeft hij het adres aan waar hij op te vinden is ( zet die vast in je router)
7. Ga naar je Home Assistant instalatie, deze zal gaan melden dat er een nieuw device gekoppeld is. En voeg deze toe.
8. Als het goed is gaat de print connectie maken met Github om de laatste versie binnen te halen, en daardoor ook toe te voegen aan Esphome
9. Maak een map aan in je config map via de verkenner en noem deze ``` utility_meter ``` en plaats daar weer een tekst bestand in en hernoem deze naar utility.yaml, en voeg onderstaande code daar in toe. En sla deze op( of download hem uit deze repro) en plaats hem in die map. (Code die onder 10 staat)
10. Voeg de volgende code toe aan je 
``` configuration.yaml   ```
<br> ``` utility_meter: !include utility_meter/utility.yaml ```

``` yaml
#utility_meter:
### watermeter  S0 meter
  waterverbruik_kwartier:
    source: sensor.watermeter_totaal
    cycle: quarter-hourly
  waterverbruik_per_uur:
    source: sensor.watermeter_totaal
    cycle: hourly
enz...
```
Die in de file staan in de map [utility_meter/utility.yaml](https://github.com/huizebruin/s0tool/blob/main/utility_meter/utility.yaml) 

12. Optioneel om te zien of er nieuwe updates zijn, kun je de volgende sensor aanmaken in je configuration.yaml:<br>
(of je kopieert de sensor file uit de sensor map en plaatst dat allemaal in je eigen configuratie).
```yaml
#sensor: # ervoor weg als dit je eerste sensor is
  - platform: rest
    resource: https://api.github.com/repos/huizebruin/s0tool/releases/latest
    name: s0tool_versie_github
    value_template: '​{{ value_json.tag_name }}​'

```
Deze versie kun je dan vergelijken met de entity "sensor.s0tool_versie".<br>
Deze 2 staan ook in de sensor map op deze Github.

13. Herstart Home Assistant nog een maal om alles toe te kunnen voegen aan je Lovelace scherm.

14. Voeg deze kaart toe om automatisch een update te krijgen op je dashboard, daarmee weet je of je de laatste versie gebruikt.

``` yaml
type: conditional
conditions:
  - entity: sensor.s0tool_gelijk_github
    state_not: 'True'
card:
  type: markdown
  content: De s0tool is niet up to date met de GitHub versie.
```
***




## Blueprint voor update meldingen.
Hiermee kun je een automation maken waardoor je melding krijgt als er een nieuwe versie online staat op Github.
Je moet dan wel alle bovenstaande sensoren hebben toegevoegd.
<br>
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgist.github.com%2Fhuizebruin%2Fcc87171b7974517497fbb55cd4bef83e)


***
## Aanpassen van de meter stand
Voor het aan passen van de water meter stand : 
[![Open your Home Assistant instance and show your service developer tools with a specific service selected.](https://my.home-assistant.io/badges/developer_call_service.svg)](https://my.home-assistant.io/redirect/developer_call_service/?service=ESPHome%3A+s0tool_meterstand_water)
<br><br>
Voor het aanpassen van je kwh meter stand : [![Open your Home Assistant instance and show your service developer tools with a specific service selected.](https://my.home-assistant.io/badges/developer_call_service.svg)](https://my.home-assistant.io/redirect/developer_call_service/?service=ESPHome%3A+s0tool_meterstand_kwh)
<br><br>
Of deze optie en dan zoeken naar de juiste meter en dan aanpassen,<br> Hier kan je alle meterstanden updaten: 
[![Open your Home Assistant instance and show your service developer tools with a specific service selected.](https://my.home-assistant.io/badges/developer_call_service.svg)](https://my.home-assistant.io/redirect/developer_call_service/?service=Nutsmeter%3A+Calibrate)
<br>

****
## Update-functie
04-08-2022 : <br> Ik werk aan een functie om deze tool altijd uptodate te houden met de laatste versie die op github staat. Dit is gelukt en is te doen via het ESPHome

***

Veel plezier met deze tool.<br>
Eventuele toevoegingen / verbeteringen <br> mogen via <b>[Pull requests](https://github.com/huizebruin/s0tool/pulls)</b> aangevuld worden.<br> 
Of via <b>[issues](https://github.com/huizebruin/s0tool/issues) </b> aangevraagd en of toegevoegd worden.
<br><br><b>
Wobbe van Huizebruin.nl</b>
<br><br>
Voor meer informatie en aansluitschema's etc kijk dan even op de [website](https://www.huizebruin.nl/home-assistant/wat-is-de-s0tool/).
***

## Meewerken.
Dit is een actief open-sourceproject. <br>
We staan ​​altijd open voor mensen die de code willen gebruiken of eraan willen bijdragen.

Wie werken er nog meer aan dit project : <br>
![GitHub contributors](https://img.shields.io/github/contributors/huizebruin/s0tool?style=plastic)<br>


****

## License

MIT License

Copyright (c) 2021 / 2023 Huizebruin

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

***

<a href="https://tc.tradetracker.net/?c=27&amp;m=39668&amp;a=385034&amp;r=&amp;u=" target="_blank" rel="sponsored nofollow">Geld verdienen met je site. Start nu, meldt je hier aan.</a>




[commits-shield]: https://img.shields.io/github/commit-activity/m/huizebruin/s0tool.svg
[commits]: https://github.com/huizebruin/s0tool/commits/main
[github-last-commit]: https://img.shields.io/github/last-commit/huizebruin/s0tool.svg?style=plasticr
[github-master]: https://github.com/huizebruin/s0tool/commits/main
[license-shield]: https://img.shields.io/github/license/huizebruin/s0tool.svg
[discord-shield]: https://img.shields.io/discord/723629686093119650.svg?logo=discord&color=7289da
[discord]: https://discord.gg/bN8rC7gEng
[contributors-url]: https://github.com/huizebruin/s0tool/graphs/contributors
[contributors-shield]: https://img.shields.io/github/contributors/huizebruin/s0tool.svg
[forks-shield]: https://img.shields.io/github/forks/huizebruin/s0tool.svg
[forks-url]: https://github.com/huizebruin/s0tool/network/members
[stars-shield]: https://img.shields.io/github/stars/huizebruin/s0tool.svg
[stars-url]: https://github.com/huizebruin/s0tool/stargazers
[issues-shield]: https://img.shields.io/github/issues/huizebruin/s0tool.svg
[issues-url]: https://github.com/huizebruin/s0tool/issues

