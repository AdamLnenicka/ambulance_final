# Ambulance

Tato aplikace umožňuje spravovat rozpis doktorů v ambulanci.


  - **Poznámka:** v případě divnýho chování jak aplikace tak souborů dej vědět, já aplikaci testoval jak se dalo, vše se zdá v normě.

    
## Obsah

### Soubor `doktoři.txt`
- Obsahuje seznam doktorů.
- **Pro přidání:** Edituj soubor přidáním nového doktora na nový řádek.
- **Pro odstranění:** Smaž odpovídající řádek.

### Nepřítomnosti
- Při zadání jednodenní nepřítomnosti je nutné zadat stejné datum do polí `Datum od` i `Datum do`.
- Nepřítomnosti se spolu s celým rozpisem uloží do souboru `rozpis.txt` pouze v okamžiku generování PDF, ne při každé změně.
  - **Poznámka:** V případě, že je aplikace ukončena bez vygenerování PDF, zadané nepřítomnosti se neuloží.

### Zobrazení posledního rozpisu
- Pomocí tlačítka `Zobrazit poslední rozpis` se do programu nahraje obsah rozpisu (ze souboru `rozpis.txt`) z okamžiku posledního generování PDF.

### Generování rozpisu
- Tlačítko `Generovat rozpis` vygeneruje soubor `rozpis.pdf` se zadanými nepřítomnostmi .
  - **Poznámka:** Název PDF souboru obsahuje datum a čas vygenerování ve formátu `den.mesic.rok_hodina-minuta-vterina`.

## Instalace

1. **Stáhni si repozitář:**
    - Klikni na zelenou ikonku `Code` -> `Download ZIP`.

2. **Extrahuj ZIP:**
    - Extrahuj tam, kde chceš program mít, třeba na plochu.
    - Ve složce `dist` je spustitelný soubor `ambulance.exe`.
    - Pokud chceš jednoduchého zástupce na ploše, stačí pravým tlačítkem kliknout na ambulance.exe (možná shif+pravé tlačítko, tak to mám já) a vytvořit ho na ploše. Pak si můžeš složku se soubory hodit kam chceš, ale závislosti musí zůstat ve složce kde jsou. Pdf se ti tam budou generovat taky.

3. **Spusť aplikaci:**
    - Otevři složku `dist` a spusť aplikaci přes soubor `ambulance.exe`, nebo přes vytvořeného zástupce.
