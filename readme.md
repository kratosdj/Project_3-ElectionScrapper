
# Python Election-Scrapper
## ENGETO Projekt 3
Závěrečný projekt pro Engeto OPA.

Tento projekt scrapuje výsledky voleb z roku 2017 ze stránek Volby.cz a následně je exportuje do CSV souboru.

## Requirements
Pro nainstalovaní potřebných balíčků se doporučuje vytvořit virtuální prostředí příkazem ve složce se soubory Python.

    python -m venv ./venv
   
Následně použít

    python -m pip install -r requirements.txt

Na některých zařízení Windows je možné, že příkaz "python" je nahrazen příkazem "python3"

## Spuštění
Pro zapnutí programu použijeme příkaz

    python election1.py
Po spuštění se zobrazí ![enter image description here](https://i.ibb.co/7v9zxBx/Screenshot-2022-04-19-at-7-34-38.png)
Zadejte váš požadovaný Kraj. Pokud bude platný zobrazí se dotazovací tabulka, do které zapíšeme název souboru který se vygeneruje.
![enter image description here](https://i.ibb.co/mH6K5pG/Screenshot-2022-04-19-at-7-38-02.png)
Dále jen Enter a počkáme si na výsledky.
![enter image description here](https://i.ibb.co/y5P3HtM/Screenshot-2022-04-19-at-7-38-54.png)

## Changes
Engeto:
1.  Výsledný soubor budete spouštět pomocí  **2 argumentů**  (ne pomocí funkce  `input`). První argument obsahuje  **odkaz**, který územní celek chcete scrapovat (př.  [územní celek Prostějov](https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103)  ), druhý argument obsahuje  **jméno**  výstupního souboru (př.  `vysledky_prostejov.csv`)

Osobně sem se rozhodl, že mi přijde jako velice nevhodné pro takovýto program aby jej člověk spouštěl s argumenty na které se lze dotázat i po spuštění programu, proto jsem tento krok vynechal a nahradil ho zadáním těchto dvou argumentů přímo v programu místo mimo něj.

## Finally

That's it... Enjoy
