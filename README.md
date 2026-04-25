
# Voron 2.4 350mm "Beštia" 48V Edition 🐉

Tento repozitár obsahuje konfiguráciu a dokumentáciu pre vysoko modifikovanú 3D tlačiareň **Voron 2.4 R2**. Cieľom tohto buildu je dosiahnutie maximálnej rýchlosti, tuhosti a inteligentného monitorovania tlače pomocou špičkových komponentov a 48V architektúry.

## 🚀 Technická špecifikácia

### Riadenie a Elektronika
* **MCU:** BTT Manta M8P V2 (32-bit control board)
* **Host:** BTT CB2 (Compute Board)
* **Napájanie:** 48V systém pre drivery motorov
* **Drivery:** BigTreeTech TMC5160T Pro (vysokonapäťové drivery pre X/Y)
* **Motory:** LDO Motor Kit V7 (High-temp, high-torque)
* **Displej:** BTT LCD 7" HDMI Touch v1.1
* **Toolhead interface:** BTT SB2240 CAN Bus (integrovaný TMC2240)

### Mechanika a Konštrukcia
* **Gantry:** Funsorr Metal CNC X-Beam Ultra Light
* **Výstuhy:** Titánové výstuhy rámu pre maximálnu tuhosť
* **X-os:** All-metal CNC idlers & držiaky
* **Lineárne vedenie:** Turui Linear Guides (Rust proof 350mm verzia)
* **Dvere:** BTT CNC ChaoticLab Door Kit
* **Senzor podložky:** CNC ChaoticLab Tap Sensor V2

### Toolhead a Senzory
* **Printhead:** Stealthburner s BTT KNOMI 2 (interaktívne UI)
* **Senzory prostredia:** SGP senzory pre monitorovanie kvality vzduchu (VOC)
* **Senzor filamentu:** BTT Smart Filament Sensor
* **Chladenie elektroniky:** 4x silné priemyselné ventilátory pre spodný deck

## 🎨 Vizuálny štýl a Osvetlenie
* **Farebná schéma:** Červeno-čierna klasika (Red/Black Voron theme)
* **Osvetlenie:** 2x 270mm WS2812B-RGB Light Bar (adresovateľné LED pásiky)
* **Status monitor:** KNOMI 2 animácie integrované v Stealthburneri

## 🧪 Používané materiály (Testovacie vzorky)
Pre kalibráciu a bežnú prevádzku sú aktuálne overené nasledovné materiály:
* **Creality CR-PLA Black** (vynikajúca pre testy tuhosti)
* **eSUN ePLA+HS** (vysokorýchlostné PLA)
* **Plasty Mladeč (Biela PLA)**

## 🔧 Klipper Konfigurácia (Hlavné črty)
* Využitie **48V** pre extrémne zrýchlenia bez straty krútiaceho momentu.
* **Input Shaper** optimalizovaný pre ultra-ľahkú CNC gantry a titánové výstuhy.
* Makrá pre **SGP senzory** – automatická regulácia filtrácie pri detekcii výparov.
* Dynamické RGB podsvietenie pre vizuálnu diagnostiku stavu tlačiarne.

---
*„Beštia nie je len tlačiareň, je to demonštrácia sily a precíznosti.“*
