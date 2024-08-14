# Ambulance

Tato aplikace umožňuje spravovat rozpis doktorů v ambulanci.

# Obsah

Soubor doktoři.txt obsahuje seznam doktorů
    pro přidání edituj soubor přídáním nového doktora na nový řádek
    pro odstranění doktora smaž odpovídající řádek

Při zadání jednodenní nepřítomnost je nutné zadat datum od a datum do stejný den.

Nepřítomnosti se spolu s celým rozpisem uloží do souboru rozpis.txt pouze v okamžiku generování pdf, ne při každé změně.
    V případě, že je aplikace ukončena bez vygenerování pdf, zadané nepřítomnosti se neuloží.

Pomocí tlačítka zobrazit poslední rozpis se do programu nahraje obsah rozpisu (ze souboru rozpis.txt) z okamžiku posledního generování pdf.

Tlačítko Generovat rozpis vygeneruje soubor rozpis.pdf se zadanými nepřítomnostmi.
    název .pdf souboru obsahuje datum a čas vygenerování ve formátu den.mesic.rok_hodina-minuta-vterina


## Instalace

1. Stáhni si repozitář:
    Zelená ikonka code -> download zip

2. Extrahuj zip:
    Extrahuj tam, kde chceš program mít, třeba na plochu.
    ve složce dist je spustitelný soubor ambulance.

4. Spusť aplikaci přes ambulance.exe soubor.
