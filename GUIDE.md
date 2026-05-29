# 📘 Beštia Guide: System Setup, eMMC & Boot Screen

[Slovenská verzia](#slovenská-verzia) | [English Version](#english)

---

> 📖 **PRIPRAVOVANÁ KNIHA / UPCOMING BOOK:** > **KÓD, PLAST A SLOBODA: KOMPLETNÝ MANUÁL OPEN-SOURCE 3D TLAČE** > *(Podtitul: Ako si postaviť, oživiť a ovládnuť Voron v roku 2026)* >
> Táto kapitola je skrátenou ukážkou z pripravovanej knihy.  
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

### 🖥️ Vlastná Bootovacia Obrazovka (Armbian)
Štandardný štartovací proces Armbianu je plný textových výpisov jadra a obrázkov tučniakov. Pre čistý a profesionálny vzhľad "Beštie" som si systém upravil tak, aby počas bootovania zobrazoval len moje vlastné logo (splash screen). Keďže CB2 nevyužíva klasický `/boot/config.txt` ako Raspberry Pi, postup je odlišný.

Celý postup čistenia U-Boot výpisov (úprava `armbianEnv.txt`) a nasadenia loga cez nástroj `fbi` som spísal do detailného dokumentu:
👉 **[Stiahnuť: Kompletný návod na zmenu bootovacieho loga (PDF)]([Navod_Zmena_Boot_Loga_Armbian.pdf](https://github.com/flyer05/Bestia-Voron-2.4/tree/main/Mods/Navod_Zmena_Boot_Loga_Armbian.pdf))**

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
4. **Finalization:** Once finished, disconnect the cable, remove the jumper, and reboot.

### 🖥️ Custom Boot Screen (Armbian)
The standard Armbian boot process is cluttered with kernel logs and Tux penguins. To achieve a clean, professional look for "Beštia," I configured a custom splash screen. Since the CB2 doesn't use the standard Raspberry Pi `/boot/config.txt`, the setup is quite different.

I have documented the complete process of clearing U-Boot outputs (via `armbianEnv.txt`) and setting up the logo using the `fbi` utility in a detailed guide:
👉 **[Download: Custom Boot Logo Setup Guide (PDF - Slovak)](Navod_Zmena_Boot_Loga_Armbian.pdf)**

---

## 📚 Viac informácií o knihe

Kniha **„KÓD, PLAST A SLOBODA“** vás prevedie kompletným procesom stavby moderného Voronu. Od výberu skrutiek až po pokročilé 48V architektúry a slovenské lokalizácie softvéru.

**Sledujte tento repozitár pre informácie o možnostiach predobjednávky!**
