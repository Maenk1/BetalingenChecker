# BetalingenChecker

Een eenvoudig en gebruiksvriendelijk programma om te controleren wie heeft betaald en wie nog niet — gebaseerd op Excel-gegevens van wie moet betalen en KBC-betalingsuitvoer.

Perfect voor clubs, verenigingen, gezamenlijke reizen of elke situatie waarbij je snel wil weten wie al dan niet heeft bijgedragen.

---

## 📋 Hoe gebruik je BetalingenChecker?

Volg deze stappen om de applicatie correct te gebruiken:

### 1. Download & Installeer
- Download het laatste release ZIP-bestand.
- Pak het uit naar een map van jouw keuze, bijvoorbeeld:  
  `C:\BetalingenChecker\`

### 2. Vul het `inputdata.xlsx` bestand in
- Open het bestand `inputdata.xlsx`.
- Ga naar het vakje **"Evenement (of varianten op namen)"** en vul daar de naam van het evenement in + mogelijke varianten zoals:
  - `bierfiets`
  - `bier fiets`
  - `fietsen +20`
  - `feestje juni`

  Dit zorgt ervoor dat de tool automatisch de juiste overschrijvingen kan herkennen.

- Onder **"Mensen die moeten betalen"** vul je de voornamen in van de personen die iets verschuldigd zijn.
- Onder **"Bedrag"** zet je het bedrag dat elk persoon moet betalen.
- Sla het bestand op.

### 3. Exporteer gegevens uit KBC Touch
- Log in op [KBC Touch](https://www.kbc.be/ondernemen/nl/product/betalen-en-betaald-worden/rekeninginformatie/rekeningafschriften.html ).
- Klik bovenaan op **Rekeningafschriften**.
- Selecteer de relevante periode en kies voor **Exporteer naar CSV**.
- Download het bestand.

> Link direct naar KBC exportfunctie:  
> https://www.kbc.be/ondernemen/nl/product/betalen-en-betaald-worden/rekeninginformatie/rekeningafschriften.html #:~:text=In%20KBC%20Touch,-Zo%20werkt%20het&text=Klik%20bovenaan%20op%20Rekeningafschriften%2C%20en,je%20bestandsformaat%20(PDF%20of%20CSV)

### 4. Zet het KBC-bestand om naar Excel
- Open het gedownloade `.csv` bestand met Excel.
- Ga naar **Bestand > Opslaan Als**.
- Zoek naar de map waar je `BetalingenChecker.exe` hebt staan.
- Geef het bestand de naam: `kbcdata.xlsx`
- Kies als bestandsformaat: **Excel-werkmap (.xlsx)**
- Sla het op.

> ⚠️ Let op: als het bestand een andere naam of indeling heeft, werkt het programma mogelijk niet!

### 5. Start de applicatie
- Dubbelklik op `BetalingenChecker.exe`.
- Upload via de GUI:
  - `inputdata.xlsx`
  - `kbcdata.xlsx`
- De applicatie toont een samenvatting van wie heeft betaald, wie niet, en of er afwijkende bedragen zijn.
- Download tenslotte het Excel-resultaat.

---

## 💡 Tips
- Zorg dat alle bestanden in dezelfde map staan.
- Werk altijd met **voornamen** in `inputdata.xlsx` – dit vergroot de kans op een correcte match.
- Indien nodig, kun je handmatig controleren of de mededelingen in KBC voldoende info bevatten (zoals naam of referentie).

---

## © Jasper Huyghe
Voor vragen, feedback of suggesties:  
📧 [jasper.huyghe@outlook.be](mailto:jasper.huyghe@outlook.be)
