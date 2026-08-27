# Smart-Zero-To-Grid-Controller

![Smart Zero To Grid Controller in action.](/images/0.gif)

[![License: GPL v2](https://img.shields.io/badge/License-GPL_v2-orange.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0)
[![C Standard](https://img.shields.io/badge/C-99-blue.svg)](https://en.cppreference.com/w/c/language/history)
[!Version](https://img.shields.io/badge/Version-demo_1.0-green.svg)


test
test2

## Inleiding

Netbeheerders en energiebedrijven roepen huishoudens op om eigen opgewekte stroom door zonnepanelen niet terug te leveren aan het elektriciteitsnet maar zoveel mogelijk zelf te verbruiken wanneer de zon schijnt. Zij doen dat omdat zij zien dat het elektriciteitsnet overbelast is. Het project wat hier beschreven is kan hierbij helpen.

## Wat doet het

Een slimme meter geeft via de P1 interface aan hoeveel stroom er verbruikt of teruggeleverd wordt. Deze fysieke interface stuurt elke seconde een exacte update van uw elektriciteitsverbruik naar buiten. Zodra uw zonnepanelen meer stroom opwekken dan uw huishouden op dat moment verbruikt, registreert de slimme meter dit direct als een negatief verbruik: u levert stroom terug aan het elektriciteitsnet.

### Draadloze aansturing naar de dimmer

In plaats van deze energie terug te leveren aan het net, vangt een P1-transmitter deze live data op. Dit apparaat communiceert draadloos met een slimme, traploze dimmer. Deze dimmer is direct gekoppeld aan een elektrische kachel of een elektrisch verwarmingselement in uw boiler.

### Energie omzetten in warmte

Zodra het systeem via de P1-meter detecteert dat er bijvoorbeeld 400 watt wordt teruggeleverd, stuurt de regelaar de dimmer aan. De dimmer schakelt vervolgens 400 watt naar een boiler of kachel. Verandert de bewolking of zet u in huis een koffiezetapparaat aan dan reageert het systeem in een seconde. De dimmer schroeft het vermogen direct terug om te voorkomen dat u op dat moment dure stroom van het net moet inkopen.

Het grote voordeel hiervan is dat u overtollige elektriciteit omzet in thermische energie (warm water of een warme kamer). Uw boiler werkt zo als een 'thermische batterij'. Hierdoor minimaliseert u de teruglevering naar het net, vermijdt u eventuele terugleverkosten van uw energieleverancier en verlaagt u direct uw gas- of energierekening. Zo haalt u het maximale rendement uit uw eigen zonnepanelen.

## P1 transmitter

<img src="/images/IMG_20260826_135013_500.jpg" width="200">

## Controller

![Dimmer.](/images/IMG_20260826_135603_042.jpg)

![Smart Zero To Grid Controller no load/ load.](/images/5.gif)