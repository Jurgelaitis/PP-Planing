# PP-Planner — EPSO-G Grupės Metinis Pirkimų Planavimo Įrankis

Pažangus AI pagrindu veikiantis metinis pirkimų planavimo įrankis,
skirtas EPSO-G grupės įmonių pirkimų iniciatoriams, organizatoriams
ir vadovybei — individualiam ir centralizuotam pirkimų valdymui.

---

## Apie projektą

**UAB EPSO-G įmonių grupė** — Lietuvos energetikos sektoriaus
holdingo grupė, kurią sudaro:

| Įmonė | Teisinis statusas | Taikomas įstatymas |
|---|---|---|
| UAB EPSO-G | Perkančioji organizacija | VPĮ |
| LITGRID AB | Perkantysis subjektas | PĮ (PSĮ) |
| AB „Amber Grid" | Perkantysis subjektas | PĮ (PSĮ) |
| UAB „Energy cells" | Perkantysis subjektas | PĮ (PSĮ) |

Įrankis naudojamas dviem lygmenimis:
- **Individualiai** — kiekvienos įmonės metinio pirkimų plano rengimui
- **Centralizuotai** — grupės bendrų pirkimų konsolidavimui ir analizei

---

## Pagrindinės funkcijos

### 📥 Duomenų valdymas
- Duomenų importas iš **Excel / PDF** formatų (viena, kelios ar
  visos grupės įmonės vienu metu)
- Rankinis atskirų pirkimų duomenų įvedimas
- Išsaugotų pirkimų korekcijų atlikimas
- Sinchronizacija su Doclogix DVS duomenų laukais

### ✅ Duomenų kokybės tikrinimas
- Pirminių duomenų validacija ir neatitikimų identifikavimas
- Automatinis pirkimo inicijavimo ir pradžios datų apskaičiavimas
  iš nurodytos sutarties datos (pagal PSĮ / VPĮ terminus)
- Trūkstamų laukų ir klaidingų verčių žymėjimas

### ⚖️ Pirkimų būdų analizė (įmonės lygmuo)
- Automatinė pirkimų būdų analizė pagal VPT verčių skaičiavimo
  taisykles kiekvienai įmonei individualiai
- Pasiūlymai dėl atskirų pozicijų grupavimo
- Pirkimų organizavimo taisyklių atitikimo tikrinimas (VPĮ / PĮ)
- Rizikų identifikavimas ir rekomendacijos

### 🔗 Centralizavimo analizė (grupės lygmuo)
- EPSO-G grupės įmonių pirkimų planų konsolidavimas
- Panašių pirkimų identifikavimas ir grupavimo pasiūlymai
- Centralizuotų pirkimų galimybių analizė
- Apjungimo, skaidymo ar kitokio organizavimo rekomendacijos
- Sutaupymų potencialo įvertinimas

### 📊 Ataskaitų generavimas
- Metinio pirkimų plano ataskaita (Excel / PDF)
- Centralizavimo galimybių suvestinė
- Pirkimų būdų analizės ataskaita
- Vadovybei skirta vykdomoji suvestinė (Executive Summary)

---

## Papildomi siūlomi Doclogix DVS laukai

Siekiant efektyvesnės ateities analitikos, rekomenduojama į
Doclogix DVS įtraukti šiuos papildomus duomenų laukus:

| Laukas | Pagrindimas |
|---|---|
| **Pirkimo kategorija (CPV grupė)** | Centralizavimo analizei |
| **Strateginis prioritetas** | Vadovybės sprendimams |
| **Tiekėjų skaičius rinkoje** | Konkurencingumo vertinimui |
| **Ankstesnio pirkimo nuoroda** | Tendencijų analizei |
| **Sutarties trukmė (mėn.)** | Atnaujinimo planavimui |
| **Rizikos lygis** | Prioritetų nustatymui |
| **Centralizavimo potencialas** | Grupės analizei |
| **ESG kriterijų taikymas** | Tvarumo ataskaitoms |

---

## Techninė bazė

- 🤖 **AI analizė** — Claude API centralizavimo ir pirkimų būdų
  analizės moduliams
- 📊 **Duomenų apdorojimas** — Excel / PDF importas ir eksportas
- 🌐 **Platforma** — naršyklėje veikiantis įrankis (be diegimo)
- 🔒 **Duomenų sauga** — visi duomenys apdorojami saugiai

---

## Teisinė bazė

- LR Viešųjų pirkimų įstatymas (VPĮ)
- LR Pirkimų, atliekamų vandentvarkos, energetikos, transporto ar
  pašto paslaugų srities perkančiųjų subjektų įstatymas (PĮ / PSĮ)
- Viešųjų pirkimų tarnybos (VPT) rekomendacijos ir metodinė medžiaga
- VPT pirkimų verčių skaičiavimo taisyklės

---

## Vertė organizacijoms

> **Pirkimų iniciatoriams** — struktūruotas, patogus plano rengimas
> su automatiniais skaičiavimais ir validacija.

> **Pirkimų organizatoriams** — visų įmonių planų konsolidavimas,
> centralizavimo galimybių identifikavimas, laiko taupymas.

> **Vadovybei** — aiški, duomenimis grįsta informacija teisingiems
> sprendimams dėl pirkimų organizavimo priimti.

> **EPSO-G grupei** — centralizuotų pirkimų efektyvumas, sutaupymai
> ir visiškas teisinis atitikimas VPĮ / PĮ reikalavimams.

---

## Failai

| Failas | Aprašymas |
|---|---|
| `index.html` | Pagrindinis įrankio failas |
| `README.md` | Projekto aprašymas |
| `modules/` | Analizės ir validacijos moduliai |
| `templates/` | Excel / PDF šablonai |

---

## Statusas

🚧 Aktyviai kuriama

## Atsakingas

Arūnas Jurgelaitis — Head of Procurement, Litgrid AB / EPSO-G grupė
