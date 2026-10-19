# 🎓 RapportRadar — Belgische Middelbare School Punten Tracker

[![Live Website](https://img.shields.io/badge/Website-Live%20op%20GitHub%20Pages-success?style=for-the-badge&logo=github)](https://roelwuytack-bot.github.io/belgische-school-puntentracker/)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile%20%7C%20Tablet-blue?style=for-the-badge)]()
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Lokaal%20%28Geen%20Cloud%29-brightgreen?style=for-the-badge)]()
[![License: MIT](https://img.shields.io/badge/Licentie-MIT-purple?style=for-the-badge)](LICENSE)

> Een modern, razendsnel en visueel dashboard om al je schoolpunten bij te houden, berekend volgens het officiële Vlaamse onderwijssysteem (40% Semester 1 / 60% Semester 2, DW/PW-weging en lesurencoëfficiënten).

👉 **[🌐 Open RapportRadar Direct in je Browser](https://roelwuytack-bot.github.io/belgische-school-puntentracker/)** *(werkt meteen op gsm, tablet en laptop!)*

---

## ✨ Waarom RapportRadar?

In het Vlaams secundair onderwijs telt niet elke toets even zwaar mee: vakken hebben verschillende lesuren, sommige vakken hebben examens (50% DW / 50% PW) en andere zijn 100% gespreid geëvalueerd. **RapportRadar berekent automatisch je exacte jaartotaal en waarschuwt je tijdig voor buizen en tekortpunten.**

### 🌟 Belangrijkste Functies

- ⚖️ **Officieel Vlaams Rekenmodel:**
  - **Semester 1 (40%)** en **Semester 2 (60%)**.
  - **Gespreide evaluatie (100% DW)** voor vakken zoals Godsdienst en LO.
  - **Examenvakken (50% DW + 50% PW/VP)** voor theorie- en praktijkvakken.
  - **Gewogen jaargemiddelde** automatisch berekend op basis van je aantal wekelijkse lesuren (standaard 32u-rooster voor o.a. Technologische Wetenschappen & Engineering).
- 📋 **Schoolware & Smartschool Snelle Import:**
  - Plak simpelweg je gekopieerde tekst uit Schoolware of Smartschool.
  - De ingebouwde parser herkent automatisch vaknamen, datums en scores (bv. `4 / 10`, `3.5 / 9`, `9 / 20`, `17 op 20` of `85%`).
  - Opmerkingen van leerkrachten worden automatisch gefilterd zodat enkel je zuivere cijfer overblijft.
  - Inclusief controlevenster voor **manuele goedkeuring** en duplicaatdetectie.
- 🛡️ **Deliberatieradar & Tekortenoverzicht:**
  - Telt automatisch je buizen ($< 50\%$ of $< 10/20$).
  - Berekent gewogen tekortpunten op schaal 100 en schaal /20.
  - Realtime attestprognose (A-attest koers, waarschuwing bij B-attest risico of C-attest gevaar).
- 🎯 **"Wat moet ik halen?" Doelsimulator:**
  - Bereken exact welk cijfer je op je Kerst- of Juniexamen moet halen om te slagen (50%) of een streefdoel (bv. 65%) te halen.
  - Bevat ook een simulator voor je volgende dagelijkse werk-toets.
- 📊 **Grafieken & Inzichten:**
  - Staafgrafiek met 50%-slaaggrens.
  - Spindiagram (radargrafiek) met filteroptie voor hoofdvakken.
  - Vergelijking tussen Dagelijks Werk (DW) en Examenresultaten (PW).
- 🌙 **Dark & Light Mode:**
  - Keuze tussen een diep donkerblauw dashboard met glassmorphism of een warme, rustgevende lichte beige modus.
- 🔒 **100% Privacy & Veiligheid:**
  - Draait **volledig lokaal in je eigen browser** via `localStorage`.
  - Geen accounts, geen externe servers en geen tracking. Jouw punten blijven altijd uitsluitend op jouw eigen apparaat.

---

## 🚀 Hoe te gebruiken?

### 1. Online gebruiken (Aanbevolen)
Je hoeft niets te installeren. Klik op de link en begin meteen:  
👉 **[https://roelwuytack-bot.github.io/belgische-school-puntentracker/](https://roelwuytack-bot.github.io/belgische-school-puntentracker/)**

### 2. Offline opslaan als 1 bestand
Wil je de tracker offline gebruiken of doorsturen naar klasgenoten via WhatsApp, Smartschool of e-mail?
1. Open de website en klik linksboven op **`📤 Deel Blanco Tracker`**.
2. Je downloadt direct een zelfstandig `.html` bestand.
3. Dit bestand kan je zonder internetverbinding openen door erop te dubbelklikken!

---

## 📋 Punten kopiëren uit Schoolware (Voorbeeld)

Kopieer eenvoudig een overzicht uit Schoolware of Smartschool zoals dit:

```text
Frans
Wo 7/10
Toets
K | Les verbes 1
4 / 10
Opmerking:
Un point bonus inclus.

Technologische wetenschappen elektriciteit
Wo 7/10
Toets
SO2 | Toets vermogen bij 3fsenetten
3.5 / 9

Technologische wetenschappen elektriciteit
Di 6/10
Toets
SO1 | toets herhaling driefasenetten
9 / 20
