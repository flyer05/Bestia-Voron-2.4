# 📖 Chronicle – The Birth of Beštia | Kronika – Zrodenie Beštie

[Slovenská verzia](#slovenská-verzia) | [English Version](#english)

---

## Slovenská verzia
Príbeh stavby jedného z najvýkonnejších Voronov na Slovensku.

### 🏁 Fáza 1: Základy (The Frame)
Všetko to začalo rámom. Použil som kvalitné profily a dbal na dokonalú kolmosť (squaring), čo je pri rýchlostiach, ktoré plánujem, nevyhnutné. 
* *Kľúčový moment:* Osadenie strieborných **Turui nerezových koľajníc**.

### 🔩 Fáza 2: Mechanické vylepšenia (High-End Hardware)
Rozhodol som sa neísť cestou štandardu. 
* Inštalácia **Funsorr CNC Ultra Light X-Beam** výrazne znížila hmotnosť osi X.
* Pridanie **titánových výstuh (Backers)** zabezpečilo, že sa gantry nebude pri nahrievaní deformovať.

### ⚡ Fáza 3: Srdce Beštie (48V Power & Software)
Toto je technicky najnáročnejšia časť celého projektu. Vyžaduje si precízne plánovanie nielen v kabeláži, ale aj v softvérovej príprave.

* **Napájacia stratégia:** Aktuálne Beštia ožíva na **24V systéme**, aby som bezpečne dokončil mechanickú stavbu, overil funkčnosť všetkých komponentov a vyladil základné makrá. Akonáhle bude mechanika 100% otestovaná, prepínam na **48V vetvu** pre maximálny výkon.
* **Výzva (Hardware):** Správne nastavenie jumperov na doske **BTT Manta M8P V2** a zabezpečenie nadštandardného chladenia pre drivery **TMC5160T Pro**, aby bezpečne zvládli brutálny prúd dodávaný do motorov **LDO V7**.
* **Systémové jadro (CB2):** Inštalácia operačného systému nebola úplne priamočiara – musel som **naflashovať CB2 modul priamo do jeho vnútornej eMMC pamäte**, aby som dosiahol maximálnu stabilitu a rýchlosť systému oproti klasickej SD karte.
* **Softvérový stack:** Úspešne som rozbehal **Klipper** a webové rozhranie **Mainsail**. 
* **KlipperScreen & Komunita:** Nastavil som dotykový panel cez KlipperScreen. Ako autor **slovenského prekladu pre KlipperScreen** som si dal záležať na tom, aby bolo rozhranie v mojom rodnom jazyku dokonale vyladené a prístupné aj pre ostatných užívateľov v našej komunite.

### 🐉 Fáza 4: Detaily a Finalizácia
Nahodenie **Stealthburnera** s CAN Bus komunikáciou a oživenie **KNOMI 2**. Prvé pohyby a ladenie Input Shapera.

---

## English
The construction diary of one of the most powerful Voron builds.

### 🏁 Phase 1: The Foundation (The Frame)
It all started with the frame. I focused on perfect squaring, which is essential for the speeds I aim to achieve.
* *Key moment:* Installing the silver **Turui stainless steel linear rails**.

### 🔩 Phase 2: Mechanical Upgrades (High-End Hardware)
I decided to skip the standard plastic parts where it mattered.
* The **Funsorr CNC Ultra Light X-Beam** significantly reduced X-axis mass.
* **Titanium Backers** were added to eliminate thermal expansion issues.

### ⚡ Phase 3: Heart of the Beast (48V Power & Software)
The most technically demanding part of the project, requiring precise planning in both wiring and software configuration.

* **Power Strategy:** Currently, Beštia is coming to life on a **24V system** to safely complete the mechanical build, verify all components, and tune basic macros. Once the mechanics are 100% tested, I will switch to the **48V rail** for maximum performance.
* **Hardware Challenge:** Correct jumper configuration on the **BTT Manta M8P V2** board and ensuring superior cooling for the **TMC5160T Pro** drivers to handle the massive current for the **LDO V7 motors**.
* **System Core (CB2):** The OS installation was a specialized process – I had to **flash the CB2 module directly to its internal eMMC storage** to achieve peak stability and speed compared to a standard SD card.
* **Software Stack:** Successfully deployed **Klipper** and the **Mainsail** web interface.
* **KlipperScreen & Community:** Configured the touchscreen via KlipperScreen. As the **author of the Slovak translation for KlipperScreen**, I made sure the interface is perfectly tuned in my native language, benefiting the entire local community.

### 🐉 Phase 4: Details & Finalization
Installing the **Stealthburner** with CAN Bus and bringing **KNOMI 2** to life. First moves and Input Shaper tuning.

---
*To be continued... / Pokračovanie nabudúce...*
