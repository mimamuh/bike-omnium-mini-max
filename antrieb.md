# Antrieb — Omnium Mini-Max V3 (Stahl M, LilacHaze)

Maschinenlesbare Entscheidungsakte für den kompletten Antrieb (Kurbel, Innenlager, Kettenblatt, Schaltung).
Rahmen-Kontext: `rahmen_omnium_mini_max_v3_stahl_m.md`.
Fahrer-/Nutzungskontext: `fahrer.md`.
Gestaltung: `design.md`.
Stand: 2026-09-05.

Nur Angaben aus den genannten Quellen bzw. Owner-Entscheidung. Keine erfundenen Werte.

System: **1x12-fach**, mechanisch, MTB. Schaltung: Shimano XT. Kurbel/Innenlager/Kettenblatt: Hope.

---

## Status (Entscheidungsstand)

| Feld                | Wert                                                                                   |
| ------------------- | -------------------------------------------------------------------------------------- |
| Entscheidungsstatus | **Gewählt** (Komponenten festgelegt; Kaufstatus hier nicht geführt)                    |
| Konzept             | Hope-Kurbel + Hope-Innenlager + Hope-Kettenblatt; Shimano XT M8200/M8100 für Schaltung |
| Ziel-Kettenlinie    | **49 mm** (über Hope R22 Direct Mount **Standard**)                                    |
| Kurbelarmlänge      | **165 mm**                                                                             |
| Kettenblatt Zähne   | **30**                                                                                 |
| Rahmen-BB           | BSA **68 mm**                                                                          |
| Hinterbau           | **12 × 142 mm**                                                                        |

---

## Stückliste (aktuell)

| Rolle              | Modell / Variante                                             | Marke            | Quelle        |
| ------------------ | ------------------------------------------------------------- | ---------------- | ------------- |
| Kurbel             | Hope Evo 68/73 mm, **165 mm**, **silber**                     | Hope             | Einzelartikel |
| Kettenblatt        | Hope R22 Direct Mount **Standard**, **30 Zähne**, **schwarz** | Hope             | Einzelartikel |
| Innenlager         | Hope Edelstahl BSA, **30 mm** Achse, **silber** (BBSS30S)     | Hope             | Einzelartikel |
| Werkzeug BB        | Hope Innenlagerschlüssel BSA 30 mm (HTT188)                   | Hope             | Einzelartikel |
| Schalthebel rechts | SL-M8200-IR                                                   | Shimano XT M8200 | Upgrade-Kit   |
| Schaltwerk         | RD-M8200-SGS                                                  | Shimano XT M8200 | Upgrade-Kit   |
| Kassette           | CS-M8200 / CS-M8200-12, **10-51**                             | Shimano XT M8200 | Upgrade-Kit   |
| Kette              | CN-M8100, 126 Glieder + SM-CN910-12                           | Shimano XT M8100 | Upgrade-Kit   |

Upgrade-Kit laut Quelle: Shimano XT M8200 1x12-fach Upgrade-Kit I-Spec EV.

---

## Quellen (Produkte)

| Teil                                               | URL                                                                                                         |
| -------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| Hope Evo 68/73 mm Kurbelsatz                       | https://www.bike-discount.de/de/hope-evo-68/73mm-kurbelsatz-5?number=20084336-20195873                      |
| Hope R22 Kettenblatt DM Standard black 30Z (Kauf)  | https://www.bike24.de/p1917132.html?sku=3107379                                                             |
| Hope R22 DM Standard (49 mm, Spezifikation)        | https://www.bike-components.de/de/Hope/R22-Spiderless-Direct-Mount-Kettenblatt-p92752/                      |
| Hope EVO Chainline/Clearance Chart                 | `hersteller_dokumente/Kurbelsatz Hope Evo /hope_Chainline_and_Clearance_Chart_EVO.pdf`                      |
| Hope Edelstahl Innenlager 68/73/83 für 30 mm Achse | https://www.bike-discount.de/de/hope-edelstahl-innenlager-68/73/83-fuer-30mm-achse?number=20069294-20188560 |
| Hope Innenlagerschlüssel BSA 30 mm                 | https://www.bike-discount.de/de/hope-innenlagerschluessel-bsa-30mm                                          |
| Shimano XT M8200 Upgrade-Kit I-Spec EV             | https://www.bike-discount.de/de/shimano-xt-m8200-1x12-fach-upgrade-kit-i-spec-ev                            |

---

## Entscheidungsgeschichte / Begründung

### Ursprünglich geplant (nicht mehr aktuell)

Geplant war eine durchgehende Shimano-XT-Lösung vorne:

- Kurbel: Shimano XT **FC-M8100-1**, 165 mm, Hollowtech II, Kettenlinie **52 mm**, Q-Factor **172 mm**
- Kettenblatt: Shimano XT **SM-CRM85**, 30 Zähne
- Innenlager: Shimano XT **BB-MT800** Hollowtech II BSA

Diese Teile sind **nicht** mehr die aktuelle Entscheidung. Details der alten Specs werden hier nicht mehr geführt.

### Warum Wechsel auf Hope (Owner-Entscheidung)

1. **Optik:** LilacHaze-Rahmen + viel Schwarz (Rack-Webbing, Backrest-Sitz, Carbon-Felgen, Reifen). Mattschwarze XT-Kurbel hätte noch mehr Schwarz gestapelt. Hope Evo in **silber** als bewusster Akzent (siehe `design.md`).
2. **Technik (damals):** 165 mm Armlänge wie zuvor; Kettenlinie zunächst weiter **52 mm** über Boost-Blatt (an die XT-Kurbel angelehnt); BSA 68 mm am Rahmen; XT 1x12 hinten unverändert.
3. **Trade-off akzeptiert:** anderes BB (30 mm statt Hollowtech II), anderes Kettenblatt (Hope DM statt SM-CRM85), Montagewerkzeug HTT188 nötig.

### Kettenlinie — Korrektur 2026-09-05 (Owner)

Boost **52 mm** war ein Mitnahme-Effekt der XT-Boost-Kurbel (für Hinterbau **148 mm**). Der Mini-Max hat **12 × 142 mm**. Hopes EVO-Chart mappt die vorhandene Kurbel `HCEN73` so:

| Blatt-Offset | Kettenlinie | Hinterbau laut Hope-Chart |
| ------------ | ----------- | ------------------------- |
| **STANDARD** | **49 mm**   | **135 / 142**             |
| BOOST        | 52 mm       | 148                       |

Owner wechselt auf Hope R22 Direct Mount **Standard**, 30 Zähne, schwarz (Bike24 SKU **3107379**). Begründung: Kassette auf 142 sitzt weiter innen; 49 mm zielt in die Kassettenmitte. Nutzung (Hügel, Kindlast, leichte Gänge) braucht vor allem ruhigen Lauf in **39–51**. 3 mm Fehlstand sind bei 462 mm Kettenstrebe weniger spitz als am kurzen MTB — 52 mm funktionierte oft, war aber nicht die passende Linie.

Boost-Blatt (montiert gewesen) bleibt als Ersatzteil; nicht mehr die aktuelle Wahl.

### Kettenlinie — Quellen (nicht vermischen)

| Quelle                                                                 | Angabe                                 |
| ---------------------------------------------------------------------- | -------------------------------------- |
| Hope Evo 68/73 mm (Bike-Discount, Kurbelseite)                         | **49 mm** (ohne Blatt-Offset)          |
| Hope EVO Chainline Chart, `HCEN73` + STANDARD                          | **49 mm**, Hinterbau 135/142           |
| Hope EVO Chainline Chart, `HCEN73` + BOOST                             | **52 mm**, Hinterbau 148               |
| Hope R22 DM Standard (Hope: STD Offset; bike-components; SJS Cycles)   | **49 mm** Kettenlinie                  |
| Hope R22 DM Boost (Bike-Discount; nicht mehr gewählt)                  | **52 mm** Kettenlinie für Hope-Kurbeln |
| Bike24-Schwesterseiten R22 DM ohne „Boost“ im Titel (z. B. rot/orange) | „Optimierte **49 mm** Kettenlinie“     |

**Aktuelle Wahl:** Standard-Blatt → wirksame Kettenlinie **49 mm**.  
**Nicht mehr gewählt:** Boost-Blatt 52 mm.

---

## Kurbel (aktuell)

- Hersteller: Hope Technology Ltd.
- Bezeichnung (Quelle): Hope Evo 68/73 mm Kurbelsatz
- Hersteller-Artikelnr. (gewählte Variante laut Quelle): **HCEN7365S**
- EAN (Quelle): 5056033457040
- Bike-Discount Artikel-Nr.: 20084336
- Einsatzbereich: MTB
- Kompatibilität (Quelle): 1-fach
- Achsdurchmesser: **30 mm**
- Kettenblattbefestigung: **Hope Direct Mount**
- Innenlager-Kompatibilität (Quelle): BSA 68/73
- Q-Faktor (Quelle): **167 mm**
- Kettenlinie auf Kurbelseite (Quelle): **49 mm** — mit gewähltem Standard-Blatt ebenfalls **49 mm** (Hope-Chart `HCEN73` + STANDARD)
- Gewählte Kurbelarmlänge: **165 mm**
- Weitere Längen laut Quelle (nicht gewählt): 155 / 170 / 175 mm
- Material Kurbelarme: 7150 Aluminium
- Material Achse: 7075 Aluminium
- Farbe: **silber**
- Gewicht (Quelle): 170 mm: 560 g (Herstellerangabe) — kein separates Gewicht für 165 mm auf der Quellseite
- Features (Quelle): 15 % leichtere/steifere Konstruktion; selbstabziehender Kurbelarm; 1- und 2-fach kompatibel
- Lieferumfang: 1 × Hope Evo 68/73 mm Kurbel
- **Nicht** im Lieferumfang: Kettenblatt, Spider, Innenlager

---

## Kettenblatt (aktuell)

- Hersteller: Hope Technology Ltd.
- Bezeichnung: Hope R22 Direct Mount **Standard** (Non-Boost), Narrow-Wide
- Kauf (Owner): Bike24, 30 Zähne — https://www.bike24.de/p1917132.html?sku=3107379 (Bike24-SKU **3107379**). Live-Seite hier nicht abrufbar (Bot-Schutz); Variante 30Z Owner-bestätigt. Bike24 Boost-schwarz ist ein **anderes** Produkt (`p1917138`).
- Hersteller-Artikelnr. (30 Zähne, schwarz): **RR30SP22N** — SJS Cycles (Standard Black 30T); bike-components Basis-Nr. **RR30SP22** (Farb-Suffix **N** = black, analog bisherigem Boost `RR30BSP22N`)
- EAN / UPC: **5056454963090** (bikeparts.com zu RR30SP22N)
- Ausführung: Direct Mount **Standard**, **49 mm** Kettenlinie (Hope: Direct Mount STD Offset 49 mm; bike-components: 49 mm; SJS: Standard Offset 49 mm)
- Gewählte Größe: **30 Zähne**
- Weitere Abstufungen laut Quellen (nicht gewählt): 28 / 32 / 34 / 36 Zähne
- Material: CNC-gefrästes Aluminium 7075-T6
- Farbe: **schwarz** (RR30SP22N; Gestaltung `design.md`)
- Gewicht (30T, Herstellerangabe über Shops): **61 g**
- Kompatibilität Kurbel (Quelle): Hope Direct Mount Kurbel
- Kompatibilität Kette (Quelle): 9/10/11-fach und 12-fach (SRAM Eagle, SRAM T-Type Flattop sowie **Shimano HG+**)
- Features (Quelle): asymmetrisches Zahnprofil; steiferer Stern; weniger Schmutzanhaftung
- Lieferumfang: 1 × Hope R22 Kettenblatt Direct Mount Standard
- **Nicht mehr aktuell:** Hope R22 Direct Mount **Boost** 30T schwarz (`RR30BSP22N`, 52 mm) — war montiert; siehe Entscheidungsgeschichte oben

---

## Innenlager (aktuell)

- Hersteller: Hope Technology Ltd.
- Bezeichnung (Quelle): Hope Edelstahl Innenlager 68/73/83 für 30 mm Achse
- Hersteller-Artikelnr. (silber laut Quelle): **BBSS30S**
- EAN (Quelle): 5055168084398
- Bike-Discount Artikel-Nr.: 20069294
- Gewinde: **BSA**
- Gehäusebreite (Quelle): 68 / 73 / 83 / 100 / 120 mm
- Achsdurchmesser: **30 mm**
- Einsatzbereich: MTB
- Lager: Edelstahl (austauschbare Patronenlager)
- Lagerschalen: Aluminium
- Farbe (gewählt): **silver**
- Weitere Farben laut Quelle (nicht gewählt): blue, smoke, black, orange, red, purple
- Gewicht: 102 g (Herstellerangabe)
- Features (Quelle): außenliegende Schalen; Labyrinth-Dichtung; für 30-mm-Achsen
- Lieferumfang: 1 × Hope Edelstahl Innenlager inkl. **29 mm BB Conversion-Kit**
- Montage: spezielles Werkzeug nötig — **HTT188** (nicht im Lieferumfang des Innenlagers)

### Werkzeug

- Bezeichnung (Quelle): Hope Innenlagerschlüssel BSA 30 mm
- Hersteller-Artikelnr.: **HTT188**
- EAN (Quelle): 5055168081601
- Bike-Discount Artikel-Nr.: 20075874
- Kompatibilität (Quelle): Hope BSA 30 Innenlager
- Material: Metall
- Farbe: silber
- Lieferumfang: 1 × Innenlagerschlüssel BSA 30 mm

### Beim Einbau beachten (aus Quellen + Rahmen-Constraints)

- Rahmen: BSA **68 mm** (`rahmen_omnium_mini_max_v3_stahl_m.md`).
- Spacer/Einbau gemäß Hope-Anleitung für 68 mm; Conversion-Kit **29 mm** für native Hope-30-mm-Welle nicht nötig (Kit ist für andere Achsstandards mitgeliefert).
- Nicht mit Hollowtech-II-BB (z. B. früheres BB-MT800) kombinieren.

---

## Schaltung — Shimano XT (unverändert gewählt)

### Upgrade-Kit XT M8200 1x12-fach I-Spec EV

- Hersteller: SHIMANO INC.
- Hersteller-Artikelnr.: M8200051IRAP
- Bezeichnung (Quelle): Shimano XT M8200 1x12-fach Upgrade-Kit I-Spec EV
- Antrieb: mechanisch
- Schaltwerk-Technologie: SHIMANO SHADOW ES
- Schalthebel-Befestigung: I-Spec EV
- Kassette im Kit: 10-51

#### Lieferumfang Kit

- 1 × Shimano XT SL-M8200-IR 12-fach Schalthebel I-Spec EV rechts inkl. Innenzug + Außenhülle
- 1 × Shimano XT RD-M8200-SGS 12-fach Schaltwerk
- 1 × Shimano XT CS-M8200 12-fach Kassette 10-51 inkl. Sicherungsring
- 1 × Shimano XT CN-M8100 12-fach Kette 126 Glieder inkl. Kettenschloss Quick-Link SM-CN910-12

### Schalthebel

- Modell: SL-M8200-IR
- Gruppe: XT M8200
- Shifter-Typ: Rapidfire Plus
- Befestigung: I-Spec EV (nicht kompatibel mit I-Spec II und I-Spec B)
- Montage laut Quelle: am Bremshebel
- Anbau: rechts
- Schaltstufen hinten: 12-fach
- Antriebskompatibilität: 12-fach HYPERGLIDE+
- Multi-Shift: ja (bis zu drei Gänge)
- Optische Ganganzeige: Nein
- Multi Release: Ja
- 2-Way Release: Ja
- Schaltzugeinstellung: Ja
- Funktionen laut Quelle: RAPIDFIRE PLUS, 2-WAY RELEASE, I-SPEC EV
- Kompatibel mit bisherigen 12-fach Antrieben: ja (Angabe Quelle)
- Material Griff: Aluminium
- Material Hebel: Aluminium, GFRP
- Farbe: Series color

### Schaltwerk

- Modell: RD-M8200-SGS
- Gruppe: XT M8200
- Technik: Shadow ES
- Befestigung: Direktmontage (konventionell)
- Käfiglänge: Typ-SGS lang
- Für 12-fach Kassetten mit 10–51 Zähnen
- Kompatible Kette: 12-fach HG
- Max./Min. großes Ritzel (SGS): 51 / 51 Zähne
- Max./Min. kleines Ritzel (SGS): 10 / 10 Zähne
- Käfig: Aluminium
- Material (Liste Quelle): Aluminium, GFRP, Edelstahl, Stahl
- Farbe: Series color

### Kassette

- Modell: CS-M8200 / CS-M8200-12
- Gruppe: XT M8200
- Typ: Hyperglide+
- Abstufung im Kit: 10-51 (10-12-14-16-18-21-24-28-33-39-45-51 Zähne)
- Übersetzungsbandbreite: 510 % (Angabe Quelle zur 10-51)
- Freilaufkompatibilität: Shimano Micro-Spline 12-fach MTB
- Kompatible Kette: 12-fach HG
- Sicherungsring: im Kit; Aluminium
- Hinweis (Quellseite, nicht im Kit): XT auch als 10-45 verfügbar

### Kette

- Modell: CN-M8100
- Gruppe: XT M8100
- Typ: HG / HYPERGLIDE+
- Schaltstufen hinten: 12-fach
- Hohler Stift: Ja
- Beschichtung Außenlasche: SIL-TEC
- Beschichtung Innenlasche: Chromizing
- Verschluss: Quick-Link SM-CN910-12
- Glieder im Kit: 126
- Gewicht: ca. 252 g / 116 Glieder (Herstellerangabe)
- Kompatibilität (Quelle): XT M8100/8200, SLX M7100, XTR M9100, 12-fach E-Bike
- Quick-Link Zange TL-CN10: nicht im Lieferumfang
- Passung zum Hope R22: Quelle Kettenblatt nennt Kompatibilität mit **Shimano HG+**

---

## Technologien (Shimano-Teile; nur aus Kit-Quellen)

### SHIMANO SHADOW ES

Keilförmige Bauweise; Doppelfeder-System für höhere Kettenspannung. Zugeordnet: RD-M8200-SGS.

### HYPERGLIDE+

Kassette und Kette; Schalten in beide Richtungen. Zugeordnet: CS-M8200, CN-M8100, SL-M8200-IR.

### MICRO SPLINE

Freilaufkörperstandard für 12-fach; 10-Zähne-Ritzel. Zugeordnet: CS-M8200. Siehe auch `freilaufkörper_tausch.md`.

### RAPIDFIRE PLUS / 2-Way Release / Instant Release / I-SPEC EV

Zugeordnet: SL-M8200-IR. I-Spec EV nicht mit I-Spec II / I-Spec B kompatibel.

---

## Rahmen-Constraints (Antrieb)

| Constraint                    | Wert        | Quelle                                 |
| ----------------------------- | ----------- | -------------------------------------- |
| BB                            | BSA 68 mm   | `rahmen_omnium_mini_max_v3_stahl_m.md` |
| Hinterbau                     | 12 × 142 mm | Rahmen-Datei / Laufradsatz             |
| Q-Factor/Stance (Rahmen-Spec) | 145 mm      | Rahmen-Datei                           |
| Gewählte Hope Q-Factor        | 167 mm      | Hope Evo Produktseite                  |

Hinweis: Rahmen-Spec 145 mm vs. Hope 167 mm — Differenz bewusst akzeptiert (Owner); früher XT hätte 172 mm gehabt.

---

## Offene / Beobachtungspunkte

| ID  | Thema                                                                                                              | Status                                |
| --- | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------- |
| A1  | Nach Blatt-Tausch: Freigang Kettenstrebe (Standard sitzt 3 mm weiter innen) und Kettenlauf in **39–51** unter Last | Offen                                 |
| A2  | Hope-Spacer-Anordnung am 68-mm-Gehäuse laut Hope-Anleitung                                                         | Beim Einbau (Kurbel bereits montiert) |
| A3  | Freilauf Micro Spline für CS-M8200                                                                                 | Siehe `freilaufkörper_tausch.md`      |

---

## Entscheidungs-Hinweise für LLMs

1. **Aktueller Antrieb** = Hope Evo silber 165 mm + Hope R22 **Standard** 30T schwarz (`RR30SP22N`) + Hope BBSS30S + HTT188 + Shimano XT M8200 Kit (Schaltung).
2. **Nicht** mehr planen: FC-M8100-1, SM-CRM85, BB-MT800 — nur noch als historische Notiz oben. Hope R22 **Boost** 30T (`RR30BSP22N`) ist nicht mehr die aktuelle Blatt-Wahl.
3. Kettenlinie der gewählten Kombi = **49 mm** (Standard-Blatt + Hope-Chart `HCEN73` / 135-142). Boost 52 mm war die vorherige, zum 142-mm-Hinterbau nicht passende Wahl.
4. Kette CN-M8100 bleibt; Hope R22 nennt HG+-Kompatibilität.
5. Gestaltung Akzente: siehe `design.md` (Kurbel silber, Blatt schwarz).
6. Querverweise: `tretlager.md` (kurz, verweist hierher), `freilaufkörper_tausch.md`, `fahrer.md`, `rahmen_omnium_mini_max_v3_stahl_m.md`. Gesprächsnotiz: `unterhaltungen/2026-09-05_kettenlinie_49mm_standard.md`.
7. Kettenlinie-Fakten aus zitierten Quellen (Hope-PDF im Repo, bike-components, SJS, Owner-Kauf-URL). Bike24-Produktseite selbst hier nicht gelesen (Bot-Schutz).
