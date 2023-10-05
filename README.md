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

# Toiminnanohjausjärjestelmän käyttöohjeet
## Yleistä
Kaikki painikkeet löytyvät samalta Tarjouslaskenta-välilehdeltä.

## Käyttöönoton valmistelu
Kapasiteeti-välilehdellä on valmis pohja viikkokohtaiselle kapasiteetin lisäämiselle. Tällä tarkoitetaan, kuinka paljon työkonetta voidaan kuormittaa viikkotasolla. <strong> Kapasiteetit täytyy lisätä itse, joka viikolle</strong>.
Tuntihinnat välilehdellä määritellään eri työvaiheiden hinnat. <strong>Tuntihinnat täytyy määritellä itse</strong>. Tuntihinnat- välilehdellä olevat työvaiheet vastaavat Tarjouslaskenta-välilehdellä olevia työvaiheita. Tarjouslaskennan rivejä täytettäessä hinnat käydään hakemassa vastaavan työvaiheen perusteella Tuntihinnat-välilehdeltä. (Esim. Tarjouslaskennan Tyovaihe_1 vastaa Tuntihinnat-välilehden työ1-saraketta.) Tuntihinnat-välilehden Muutyö-sarake vastaa Tarjouslaskenta-välilehdellä Muu työ-saraketta. Otsikoita voidaan muuttaa kuvaamaan paremmin käyttötarpeita.
Yritystiedot-välilehdellä käydään täyttämässä yrityksen tiedot, sekä toimitusehdot. Yrityksen tiedot haetaan tarjoukseen, lähetteeseen ja tilausvahvistukseen.

## Asiakkaan tiedot
Asiakaslista-välilehdelle pystytään lisäämään asiakkaan tiedot. Yhden asiakkaan tiedot lisätään yhdelle riville. Asiakkaat täytyy lisätä riveille, niin ettei asiakaslistaan muodostu tyhjiä rivejä. Jos lista sisältää tyhiä rivejä asiakkaiden välillä, asiakkaiden hakeminen ei onnistu.
Kun asiakas tai asiakkaat on lisätty, voidaan Tarjouslaskenta-välilehdellä hakea asiakkaan tiedot automaattisesti painamalla Hae asiakas -painiketta. Kun painiketta painetaan, aukeaa ponnahdusikkuna, johon pyydetään syöttämään yrityksen nimi. Kun yrityksen nimi syötetään, sovellus hakee kyseisen asiakkaan tiedot asiakaslista -välilehdeltä.

[![Asiakkaan lisäys](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/AsiakkaanHakeminen.gif?raw=true "Asiakkaan hakeminen")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/AsennusGif.gif?raw=true "Asiakkaan hakeminen")

## Tarjouksen rivien täyttäminen
Tarjoukseen täytetään projektin tiedot. Harmaalla värjättyihin soluihin lasketaan hinnat automaattisesti. Myös rivillä 10 olevaan vihreällä värjättyyn yhteensä sarakkeeseen tulee laskujen yhteistulos automaattisesti. Riville tulee kaikkien täytettyjen kolumnien yhteenlasketut tiedot. Sovellus ei hyväksy tyhjiä rivejä tarjouslaskennan rivejä täytettäessä. Jos kolumni jää tyhjäksi, sen arvoksi lisätään 0, kun tarjous viedään tarjouslistaan.

## Päivämäärät
Päivämäärät pitää olla muodossa YYYY/MM/DD eli vuosi/kuukausi/päivä. Tarjouksen päivämäärän sovellus luo automaattisesti. Toimitusaika muunnetaan automaattisesti tarjouslistassa viikkonumeroksi.

## Tarjouslista
Tiedot siirretään tarjouslistaan Siirrä tarjouslistaan-nappia painamalla. Tarjous viedään tarjouslistan alimmaiseksi ja tarjouksen rivien viimeisin sarakekeen checkboxit ruksitaan automaattisesti. Täällä tarjous on tallessa sillä välin kun tarjous lähetetään asiakkaalle ja saadaan sille hyväksyntä. Jos tarjousta halutaan myöhemmin muokata, sen saa haettua projektinumeron avulla Tarjouslaskenta-välilehden Hae tarjouslistasta-painikkeen avulla. Tällöin ”Viimeisin” sarakkeen checkboxien ruksit otetaan automaattisesti pois vanhasta versiosta.
Kun tarjousta on muokattu, pitää tarjous lisätä uudestaan tarjouslistaan  Siirrä tarjouslistaan-painikkeella, jolloin muokatusta tarjouksesta tulee uusi ”Viimeisin” tarjous. Myös vanha tarjous jää tarjouslistaan, jos sitä halutaan tarkastella myöhemmin.

[![Tarjouslistaan vienti](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/SiirtoTarjouslistaan.gif?raw=true "Tarjouslistaan vienti")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/SiirtoTarjouslistaan.gif?raw=true "Tarjouslistaan vienti")

## Luo tarjous, tilausvahvistus ja lähete
### Tarjous
Kun tarjouslaskenta-välilehden rivit on täytetty ja tarjous on viety tarjouslistaan voi tarjouksen viedä sen jälkeen tarjous-välilehdelle. Tarjous-välilehti sisältää Asiakkaan ja projektin tiedot sekä toimitusajat. Tarjoukseen tulee myös nimikkeet ja hinnat, sekä toiminnanohjausjärjestelmän käyttöönotossa määritelty yritysleima (Kts. käyttöönoton valmistelu), joka sisältää yrityksen tiedot.

[![Tarjous](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoTarjous.gif?raw=true "Tarjouslistaan vienti")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoTarjous.gif?raw=true "Tarjous")

### Tilausvahvistus
Tilausvahvistus luodaan silloin, kun tarjoukselle on saatu hyväksyntä. Kun tarjous vieään Tilausvahvistus-välilehdelle, sovellus käy ruksimassa tarjouslistasta "Hyväksytty"-sarakkeen. Tilausvahvistus-välilehti sisältää samat tiedot kuin tarjous-välilehti.

[![Tilausvahvistus](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoTilausvahvistus.gif?raw=true "Tilausvahvistus")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoTilausvahvistus.gif?raw=true "Tilausvahvistus")

### Lähete
Kun tarjouksen kaikki työvaiheet on valmiita voidaan tarjouksen tiedot viedä Lähete-välilehdelle. Lähete-välilehti sisältää samat tiedot kuin Tarjous- ja Tilausvahvistus-välilehdet, mutta projektin tiedoissa näkyy ainoastaan sovittu toimituspäivämäärä.

[![Lähete](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoLähete.gif?raw=true "Lähete")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoLähete.gif?raw=true "Lähete")

## Työlista
Siirrä työlistaan-painikkeella projektin tiedot viedään Työlista-välilehdelle.  Työlista-välilehdellä voidaan määritellä, millä viikolla projektin eri vaiheet tehdään. Projektin voi merkitä aloitetuksi, valmiiksi tai myöhästyneeksi.
Projektin työvaiheet menevät eri riveille, jotta työviikkojen täyttäminen pystytään jakamaan jokaiselle nimikkeelle erikseen.
Kun tarjous viedään työlistaan, sovellus kysyy oletko vienyt viimeisimmän version tarjouslistaan. Tämä pitää tarkistaa, jotta työlistaan menevät oikeat tiedot. Tarjousta vietäessä työlistaan työlista käydään läpi duplikaattien varalta. Jos työlistassa on jo työ samalla projektinumerolla, ei sitä voi viedä sinne.

[![Työlistaan vienti](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/VieTyoListaan.gif?raw=true "Työlistaan vienti")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/VieTyoListaan.gif?raw=true "Työlistaan vienti")

## Työkortti
Työkorttiin merkitään tehdyt tuntimäärät eri työvaiheille. Työvaiheita voi muokata mieleisekseen.
Kun Työkortti-painiketta painetaan, viedään sinne tarjouksen asiakkaan tiedot ja projektin numero ja nimi, sekä toimitusaika.
Tarjouksen nimikkeet lisätään osalistaan. Työlista on tarkoitettu tulostettavaksi ja työvaiheiden kestot on tarkoitus täyttää manuaalisesti.

## Tyhjennys
Tyhjennys-painikkeella tyhjennetään kaikki aikaisemmin täytetyt rivit, jotta täyttäminen voidaan aloittaa puhtaalta pöydältä. Tyhjennys ei hävitä kaavasarakkeita, eikä päivämääräsarakkeita. Päivämäärä-sarakkeiden arvot muuttuvat meneillään olevan päivän arvoksi.
