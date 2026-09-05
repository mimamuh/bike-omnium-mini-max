# Aufbauplan — Hope Kurbel, Kettenblatt & Innenlager

Omnium Mini-Max V3 Stahl M (LilacHaze) · BSA **68 mm** · Hinterbau **12 × 142 mm**

Stand: 2026-09-05 · Entscheidungsgrundlage: `antrieb.md`, `tretlager.md`, `rahmen_omnium_mini_max_v3_stahl_m.md`

---

## Deine Komponenten (Kurz)

| Teil                      | Modell                                                    |
| ------------------------- | --------------------------------------------------------- |
| Kurbel                    | Hope Evo 68/73 mm, **165 mm**, silber, 30-mm-Achse        |
| Kettenblatt               | Hope R22 Direct Mount **Standard**, **30 Zähne**, schwarz |
| Innenlager                | Hope Edelstahl BSA 30 mm, silber (**BBSS30S**)            |
| Werkzeug BB               | Hope **HTT188**                                           |
| Ziel-Kettenlinie          | **49 mm** (Standard-Blatt)                                |
| Ziel-BB-Breite über Lager | **96,5 mm** (Hope MTB-Standard)                           |

**Herstellerdokumente:** `hersteller_dokumente/Innenlager Hope/`, `hersteller_dokumente/Kurbelsatz Hope Evo /`

Kurbel und Innenlager sind bereits montiert (2026-08). **Aktueller Schritt:** Boost-Blatt gegen Standard-Blatt tauschen — Lockring **50–60 N·m** (`HC105-26T`), danach Freigang zur Kettenstrebe prüfen. Kurbel muss dafür nicht vom Rahmen.

---

## Werkzeug & Verbrauch — vorab bereitlegen

- [x] Hope Innenlagerschlüssel **HTT188**
- [ ] Drehmomentschlüssel (BB: **40–50 N·m**; Kettenblatt-Lockring: **50–60 N·m**; Preload-Klemm-Schraube: **0,6–0,8 N·m**)
- [ ] **10 mm** Innensechskant (EVO-Kurbelarm)
- [ ] **2,5 mm** Innensechskant (Preload-Klemm-Schraube)
- [ ] Hope Lockring-Werkzeug **HC105-26T** (38-mm-Stecknuss oder BB-Maulschlüssel) — **vorhanden**
- [ ] Fett (Gewinde + Lager-/Achskontaktflächen; sparsam)

**Nicht nötig für deinen Build:** 29-mm-Conversion-Kit aus der BB-Box (nur für andere Achsstandards; native Hope-30-mm-Welle).

---

## 1. Vorbereitung am Rahmen

- [ ] Rahmen sicher im Ständer; Tretlagergehäuse **68 mm** gegenprüfen (Hope-Kompatibilitätstabelle)
- [ ] **BSA-Gewinde im Rahmen vorhanden** — vor Einbau nur reinigen; Gewinde **frei von Verschmutzung und Grat**, Anlageflächen eben (Hope-Vorprüfung)
- [ ] Nur bei Problemen (schwer laufende Schalen, unebene Anlage): Gewinde nachschneiden / Facing — bei dir voraussichtlich **nicht nötig**
- [ ] Spacer-Plan festlegen (Hope BBSS30 + 68-mm-Gehäuse + EVO 133,5-mm-Achse):
  - [ ] **Antriebsseite (DS):** **1 × 2,5 mm** (BBSP106)
  - [ ] **Nicht-Antriebsseite (NDS):** **2 × 2,5 mm** (BBSP106)
  - [ ] Ergebnis: **96,5 mm** über den Lagerdichtungen (±1 mm laut Hope)
- [ ] Alle **3 mitgelieferten 2,5-mm-Spacer** aus der BB-Box zuordnen; Rest-Spacer sichern/kennzeichnen

---

## 2. Kettenblatt montieren (Werkbank — vor Kurbel am Rahmen)

> Direct-Mount-Blatt sitzt am Kurbelarm, nicht am Spider. Einbau laut Hope **vor** dem Setzen der Kurbel am Rad sinnvoll.

- [ ] Schnittstelle Kurbelarm ↔ Kettenblatt **sauber und trocken**
- [ ] **Standard**-Blatt wählen/prüfen (Ziel-Kettenlinie **49 mm**; Boost-Offset wäre 52 mm — nicht mehr gewählt)
- [ ] Splines und Gewinde **leicht fetten**
- [ ] Kettenblatt korrekt orientiert auf Antriebs-Spline setzen
- [ ] Lockring-Unterlegscheibe (Shim) einlegen; Lockring **von Hand** anstarten (darf leicht laufen)
- [ ] Mit **HC105-26T** anziehen → **50–60 N·m**
- [ ] Zahnkranz visuell prüfen (kein Kippen, sauberer Sitz)

Details: `Kurbelsatz Hope Evo /Hope_EVO_Crankset_EN_FR_DE.pdf`, Exploded View `EVO_exploded_studio_002.pdf`

---

## 3. Innenlager einbauen

Quelle: `Innenlager Hope/30mmThreadedBB-EN_FR_DE_V2.pdf`, Spacer-Tabelle `BSA_threaded_WEB_2023.pdf`, EVO-Kompatibilität `2019EVOCranksBBCompatibility_ISS03_11.2019.pdf`

- [ ] Gewinde an **Schalen und Rahmen** fetten
- [ ] **Antriebsseite zuerst:** Schale mit **1 × 2,5 mm** Spacer(n) — **gegen den Uhrzeigersinn** einschrauben (Linksgewinde!)
- [ ] Schale **von Hand** anstarten, dann mit **HTT188** festziehen → **40–50 N·m**
- [ ] **Nicht-Antriebsseite:** Schale mit **2 × 2,5 mm** Spacer(n) — **im Uhrzeigersinn** einschrauben
- [ ] Ebenfalls von Hand anstarten, mit **HTT188** → **40–50 N·m**
- [ ] **2 Staubkappen** (aus BB-Lieferumfang) einsetzen
- [ ] Lager lassen sich leichtgängig drehen; keine offensichtliche Seitenspiel-Problematik

**Hope-Hinweis:** Achse läuft direkt auf dem inneren Lagerlauf — **keine** Kunststoff-Achsspacer zwischen Welle und Lager.

---

## 4. Kurbel einbauen

Quelle: `Kurbelsatz Hope Evo /Hope_EVO_Crankset_EN_FR_DE.pdf` (Montage = Umkehrung Demontage + Bildseiten in der PDF lesen)

### 4.1 Preload vorbereiten

- [ ] Preload-Klemm-Schraube (**2,5 mm**) lösen
- [ ] Preload-Mutter so weit **aufdrehen**, dass **kein Spalt** zwischen Preload-Ring und NDS-Kurbelarm bleibt (Hope Demontage-Schritt 004 rückwärts)

### 4.2 Achse einsetzen

- [ ] Kontaktflächen an **Achse und innerem Lagerlauf** leicht fetten
- [ ] NDS-Teil (Achse + linker Arm) von **links** durch das BB schieben — **nur von Hand**, kein Hammer
- [ ] Antriebs-Kurbelarm mit **180°** Versatz zum linken Arm auf die Achs-Splines setzen; Splines leicht gefettet
- [ ] Antriebs-Kurbelarm fest an die Achse drücken, Splines vollständig formschlüssig

### 4.3 Antriebsseite verschrauben (EVO selbstausziehend)

- [ ] Antriebs-**Kurbelschraube** mit **10 mm** Innensechskant **im Uhrzeigersinn** anziehen (Gegenrichtung zur Demontage)
- [ ] Bei Widerstand zieht die Schraube den Arm auf die Achse — bis der Arm voll sitzt
- [ ] **Drehmoment Kurbelschraube:** beim Einbau in `Hope_EVO_Crankset_EN_FR_DE.pdf` (Montage-Bildseiten) ablesen
- [ ] Endkappe (falls noch nicht montiert): Gewinde fetten, von Hand anstarten, mit **10 mm** festziehen → EVO-PDF bzw. Hope-Richtwert **17–20 N·m**

### 4.4 Lager preload

- [ ] Preload-Mutter **von Hand zurückdrehen**, bis sie die **Lagerdichtung/Shield** berührt — **kein sichtbarer Spalt**
- [ ] Preload-Klemm-Schraube mit **2,5 mm** → **0,6–0,8 N·m**
- [ ] **Nicht** den Auszieh-/Preload-Hebel zum Festziehen der Mutter missbrauchen (Lagerüberlastung)
- [ ] Kurbel dreht frei, **ohne** spürbares Seitenspiel

---

## 5. Prüfung nach dem Einbau

- [ ] Kurbel **360°** mehrfach durchdrehen (leichtgängig, kein Kratzen)
- [ ] Seitenspiel erneut prüfen (Preload ggf. minimal nachjustieren)
- [ ] Kettenblatt-Freigang zum Rahmen / Kettenstreben prüfen (Standard sitzt **3 mm weiter innen** als das bisherige Boost-Blatt)
- [ ] Kettenlinie **49 mm** — bei Rubbing an der Strebe oder unruhigem Lauf in 39–51 siehe `antrieb.md`
- [ ] Pedale **noch nicht** montieren, wenn Schaltung/Kette als Nächstes folgt — sonst: Pedaldrehrichtung beachten, Unterlegscheiben nutzen, **~35 N·m**

---

## 6. Was bewusst später kommt (nicht in diesem Schritt)

- [ ] Kette, Schaltwerk, Kassette (Shimano XT M8200) — eigener Aufbauplan
- [ ] Feinjustierung Schaltung und Kettenlauf
- [ ] Probefahrt

---

## Geklärt (Owner, 2026-08-29)

| #   | Thema                             | Ergebnis                                                     |
| --- | --------------------------------- | ------------------------------------------------------------ |
| 1   | Lockring-Werkzeug **HC105-26T**   | **Vorhanden**                                                |
| 2   | Drehmoment Kurbelschraube (10 mm) | Beim Einbau in EVO-PDF nachschlagen — so geplant             |
| 3   | BB-Gewinde im Rahmen              | **BSA-Gewinde vorhanden** — kein separates Facing vorgesehen |
| 4   | Kettenblatt-Offset (2026-09-05)   | **Standard / 49 mm** — Boost 52 mm nicht mehr aktuell        |

---

## Quellenverzeichnis

| Dokument                  | Pfad                                                                                   |
| ------------------------- | -------------------------------------------------------------------------------------- |
| Antrieb (Komponentenwahl) | `antrieb.md`                                                                           |
| Tretlager Kurz            | `tretlager.md`                                                                         |
| Rahmen BB 68 mm           | `rahmen_omnium_mini_max_v3_stahl_m.md`                                                 |
| BB Einbau + Spacer 68 mm  | `hersteller_dokumente/Innenlager Hope/30mmThreadedBB-EN_FR_DE_V2.pdf`                  |
| BB Spacer-Übersicht BSA   | `hersteller_dokumente/Innenlager Hope/BSA_threaded_WEB_2023.pdf`                       |
| EVO + BB Kompatibilität   | `hersteller_dokumente/Innenlager Hope/2019EVOCranksBBCompatibility_ISS03_11.2019.pdf`  |
| EVO Kettenlinie           | `hersteller_dokumente/Kurbelsatz Hope Evo /hope_Chainline_and_Clearance_Chart_EVO.pdf` |
| EVO Montage/Demontage     | `hersteller_dokumente/Kurbelsatz Hope Evo /Hope_EVO_Crankset_EN_FR_DE.pdf`             |
| EVO Exploded View         | `hersteller_dokumente/Kurbelsatz Hope Evo /EVO_exploded_studio_002.pdf`                |
