# 📘 Beštia Guide: System Setup & eMMC Flashing

[Slovenská verzia](#slovenská-verzia) | [English Version](#english)

---

> 📖 **Poznámka autora / Author's Note:** > Tento návod je skrátenou ukážkou z pripravovanej komplexnej knihy o stavbe a ladení high-performance Voron tlačiarní. Celá publikácia sa bude venovať detailom od mechaniky až po pokročilé 48V konfigurácie.  
> *© 2026 FLYER 05. Všetky práva vyhradené.*

---

## Slovenská verzia: Flashovanie BTT CB2 na vnútornej eMMC

Pre maximálnu stabilitu "Beštie" som sa rozhodol nepoužívať SD kartu, ale naflashovať systém priamo do vnútornej pamäte (eMMC) modulu CB2. Tu je postup:

### 🛠️ Čo budete potrebovať
1. **BTT CB2 modul** osadený v Manta M8P (alebo v adaptéri).
2. **USB-C kábel** pripojený k vášmu PC.
3. Softvér **RKDevTool** (pre Windows) alebo `rkdeveloptool` (pre Linux/Mac).
4. Oficiálny **OS Image** od BigTreeTech.

### 🚀 Postup v skratke
1. **BOOT režim:** Podržte tlačidlo "Boot" na module (alebo použite jumper na doske Manta) a pripojte ho k PC.
2. **Detekcia:** V RKDevTool by ste mali vidieť správu "Found One LOADER Device".
3. **Zápis:** Vyberte správny image a spustite proces "Upgrade".
4. **Finalizácia:** Po úspešnom zápise odpojte kábel, vyberte jumper a reštartujte. Systém teraz beží bleskovo priamo z vnútornej pamäte.

---

## English: Flashing BTT CB2 to Internal eMMC

For maximum stability of the "Beštia" build, I decided to bypass the SD card and flash the OS directly to the internal eMMC storage of the CB2 module.

### 🛠️ Requirements
1. **BTT CB2 module** (mounted on Manta M8P or adapter).
2. **USB-C cable** to connect to your PC.
3. **RKDevTool** (Windows) or `rkdeveloptool` (Linux/Mac).
4. Official **BTT OS Image**.

### 🚀 Quick Steps
1. **BOOT Mode:** Hold the "Boot" button on the module (or set the correct jumper on the Manta board) and connect to your PC.
2. **Detection:** RKDevTool should display "Found One LOADER Device".
3. **Writing:** Select the image file and click "Upgrade".
4. **Finalization:** Once finished, disconnect the cable, remove the jumper, and reboot. The system now boots instantly from eMMC.

---

## 📚 Chcete sa dozvedieť viac? / Want to learn more?

Tento návod pokrýva len základy. V pripravovanej knihe nájdete:
* Detailné riešenie problémov pri flashovaní.
* Optimalizáciu Linuxu pre Klipper.
* Kompletný postup slovenskej lokalizácie cez KlipperScreen.

**Sledujte tento repozitár pre informácie o vydaní! / Follow this repo for release updates!**
