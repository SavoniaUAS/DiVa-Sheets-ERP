# DiVa-Sheets-ERP

Tämä on käyttöönotto-ohje Savonia Ammattikorkeakoulun Digitalisaatio valmistavan teollisuuden yrityksissä-hankkeessa tuotettuun minimalistiseen Google Sheets-pohjaiseen toiminnanohjausjärjestelmään. Kyseisen toiminnanohjausjärjestelmän tarkoitus on simuloida teollista tilaus-tuotanto-toimitus-ketjua pienessä mittakaavassa. Sen lisäksi, että se on toimiva toiminnanohjausjärjestelmä, sen tarkoitus on myös toimia tietojärjestelmien hankintaprosessin kiintopisteenä, kun arvioidaan ostajan tarpeita liiketoimintaprosessien digitalisoimisessa.

Käyttöönottoon tarvitset
 - Google-tilin, jonka alta löydät Google Sheets-työkalun.
 - Google-sheets tiedoston, jossa toiminnanohjausjärjestelmän esimuotoillut taulukot sekä sovelluslogiikka sijaitsee. Kyseinen tiedosto löytyy myöhemmin ohjeesta siinä kohdassa, missä tarvitset sitä, sekä myös [tästä](https://docs.google.com/spreadsheets/d/1EGJta1woZkMkD_UsaVuSANaqO89cCi8ZTut7JLaQwaE/edit?usp=sharing)

## Uuden kansion luominen
Luo Google Driveen uusi kansio ja nimeä se haluamallasi tavalla. Toiminnanohjausjärjestelmä tulee toimimaan kyseisessä kansiossa. Toiminnanohjausjärjestelmä luo kyseiseen kansioon myöhemmin alikansioita, jotka sisältävät toiminnanohjausjärjestelmän tuottamia tiedostoja.

[![Uuden kansion luominen Driveen](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/uusiKansio.gif "Uuden kansion luominen Driveen")](http://https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/uusiKansio.gif "Uuden kansion luominen Driveen")

## Asennusohje

Siirry seuraavaan verkko-osoitteeseen. Osoite vie sinut toiminnanohjausjärjestelmän lukuversioon Google Sheets-palvelussa.

https://docs.google.com/spreadsheets/d/1vTNnTt1xqZNdZd5vmUF0RtPs7vUV-K_cQ9XFACXJiqk/edit?usp=sharing

Toiminnanohjausjärjestelmän lukuversiossa valitse Tiedosto/File-pudotusvalikosta Make A Copy/Kopioi tiedosto.

Valitse minkä nimen haluat asettaa tiedostolle ja aseta se omassa Google Drivessäsi aiemmin lisäämääsi kansioon. 

[![Asennus](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/AsennusGif.gif?raw=true "Asennus")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/AsennusGif.gif?raw=true "Asennus")

Tämän jälkeen toiminnanohjausjärjestelmän tiedosto löytyy Google Driven kansiosta, jonne kopioit tiedoston.

## Skriptien käyttöönotto

Seuraavaksi sinun tulee ottaa käyttöön Sheets-tiedostoon integroidut skriptit.

Skriptien tarkoituksena on toteuttaa sovellukseen sisäisesti ohjelmoitu logiikka.

Ottaaksesi käyttöön skriptit paina "Tyhjennä"-nappia Sheets-tiedoston Tarjouslaskenta-välilehdellä. Ensimmäistä kertaa nappia painaessasi, järjestelmällä voi kestää pieni hetki, jolloin se tarkistaa, onko napin painajalla lupa suorittaa toiminnanohjausjärjestelmän ohjelmakoodia.

Ensimmäistä kertaa painaessi nappia, sinulta kysytään lupaa toiminnon suorittamiseksi (Authorisation Required). Luvan antamiseksi sinun tulee painaa "Continue/Jatka".

Seuraavaksi sinulta kysytään tiliä, jolla skriptien käyttö sallitaan. Sinua varoitetaan siitä, että Google ei ole varmistanut tämän applikaation skriptejä. Tämä on normaalia, sillä kyseisen toiminnanohjausjärjestelmän logiikka ei ole suoraan Googlen kautta tarjottava palvelu, vaan se on sisällytetty tähän kyseiseen tiedostoon itsenäisesti.

Valitse ponnahdusikkunasta kohta "Advanced/Lisäasetukset" ja sinulle aukeaa varmistus, jossa voit valita "Siirry kohteeseen Sheets-ERP (vaarallinen) / Go to Sheets-ERP (unsafe)". Valitse "Siirry kohteeseen Sheets-ERP (vaarallinen) / Go to Sheets-ERP (unsafe)".

Seuraavaksi sinulle aukeaa näkymä, jossa toiminnanohjausjärjstelmä pyytää pääsyä Google-tilillesi. Toiminnanohjausjärjestelmän sisäinen logiikka vaatii kohtuullisesti oikeuksia Google Drive-palvelussa tuottaakseen tarvittavat toiminnallisuudet. Google pyytää sinua varmistamaan, että toiminnanohjausjärjestelmä on luotettava. 

Valitse näkymästä nappi "Allow / Salli"

Nyt toiminnanohjausjärjestelmän skriptit ovat käytössä ja sen käyttö voi alkaa.

[![Makrojen käyttöönotto](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/MakrojenEnablointi.gif "Makrojen käyttöönotto")](http://https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/MakrojenEnablointi.gif "Makrojen käyttöönotto")
