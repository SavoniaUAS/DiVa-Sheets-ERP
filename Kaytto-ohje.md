# Toiminnanohjausjärjestelmän käyttöohjeet
## Yleistä
Kaikki painikkeet löytyvät samalta Tarjouslaskenta-välilehdeltä.

## Käyttöönoton valmistelu
Kapasiteeti-välilehdellä on valmis pohja viikkokohtaiselle kapasiteetin lisäämiselle. Tällä tarkoitetaan, kuinka paljon työkonetta voidaan kuormittaa viikkotasolla. <strong> Kapasiteetit täytyy lisätä itse, joka viikolle</strong>.
Tuntihinnat välilehdellä määritellään eri työvaiheiden hinnat. <strong>Tuntihinnat täytyy määritellä itse</strong>. Tuntihinnat- välilehdellä olevat työvaiheet vastaavat Tarjouslaskenta-välilehdellä olevia työvaiheita. Tarjouslaskennan rivejä täytettäessä hinnat käydään hakemassa vastaavan työvaiheen perusteella Tuntihinnat-välilehdeltä. (Esim. Tarjouslaskennan Tyovaihe_1 vastaa Tuntihinnat-välilehden työ1-saraketta.) Tuntihinnat-välilehden Muutyö-sarake vastaa Tarjouslaskenta-välilehdellä Muu työ-saraketta. Otsikoita voidaan muuttaa kuvaamaan paremmin käyttötarpeita.
Yritystiedot-välilehdellä käydään täyttämässä yrityksen tiedot, sekä toimitusehdot. Yrityksen tiedot haetaan tarjoukseen, lähetteeseen ja tilausvahvistukseen.

## Asiakkaan tiedot
Asiakaslista-välilehdelle pystytään lisäämään asiakkaan tiedot. Yhden asiakkaan tiedot lisätään yhdelle riville. Asiakkaat täytyy lisätä riveille, niin ettei asiakaslistaan muodostu tyhjiä rivejä. Jos lista sisältää tyhiä rivejä asiakkaiden välillä, asiakkaiden hakeminen ei onnistu.

:white_check_mark:
![Asiakaslistan täyttö.](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Kuvat/AsiakasListaOikein.PNG "Asiakaslista oikein") 


:x:
![Asiakaslistan täyttö.](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Kuvat/AsiakasListaVaarin.PNG "Asiakaslista vaarin") 

Kun asiakas tai asiakkaat on lisätty, voidaan Tarjouslaskenta-välilehdellä hakea asiakkaan tiedot automaattisesti painamalla Hae asiakas -painiketta. Kun painiketta painetaan, aukeaa ponnahdusikkuna, johon pyydetään syöttämään yrityksen nimi. Kun yrityksen nimi syötetään, sovellus hakee kyseisen asiakkaan tiedot asiakaslista -välilehdeltä.

[![Asiakkaan lisäys](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/AsiakkaanHakeminen.gif?raw=true "Asiakkaan hakeminen")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/AsennusGif.gif?raw=true "Asiakkaan hakeminen")

## Tarjouslaskennan rivien täyttäminen
Tarjouslaskentaan täytetään nimikekohtaisesti nimikkeiden tuntimäärät, sekä hinnat. Harmaalla värjättyihin soluihin ohjelma laskee yhteishinnat automaattisesti. Myös rivillä 10 olevaan vihreällä värjättyyn yhteensä sarakkeeseen tulee laskujen yhteistulos automaattisesti. <strong>Laskutoimituksiin käytetyt kaavat on upotettu soluihin, joten soluja ei saa mennä muuttamaan</strong>.  Riville tulee kaikkien täytettyjen kolumnien yhteenlasketut tiedot. <strong>Sovellus ei hyväksy tyhjiä rivejä tarjouslaskennan rivejä täytettäessä</strong>. Jos solu jää tyhjäksi, sen arvoksi lisätään 0, kun tarjous viedään tarjouslistaan.

## Päivämäärät
Päivämäärät pitää olla muodossa YYYY/MM/DD eli vuosi/kuukausi/päivä. Tarjouksen päivämäärän sovellus luo automaattisesti. Toimitusaika muunnetaan automaattisesti tarjouslistassa viikkonumeroksi.

## Tarjouslista
Tarjouslista toimii ohjelman tietokantana. Tiedot siirretään tarjouslistaan Siirrä tarjouslistaan-nappia painamalla. Tarjous viedään tarjouslistan alimmaiseksi ja tarjouksen rivien viimeisin sarakkeen checkboxit ruksitaan automaattisesti. Täällä tarjous on tallessa sillä välin kun tarjous lähetetään asiakkaalle ja saadaan sille hyväksyntä. Jos tarjousta halutaan myöhemmin muokata, sen saa haettua projektinumeron avulla Tarjouslaskenta-välilehden Hae tarjouslistasta-painikkeen avulla. Tällöin ”Viimeisin” sarakkeen checkboxien ruksit otetaan automaattisesti pois vanhasta versiosta.
Kun tarjousta on muokattu, pitää tarjous lisätä uudestaan tarjouslistaan Siirrä tarjouslistaan-painikkeella, jolloin muokatusta tarjouksesta tulee uusi ”Viimeisin” tarjous. Myös vanha tarjous jää tarjouslistaan, jos sitä halutaan tarkastella myöhemmin. Vanhoja tarjouksia voi halutessaan poistaa myös manuaalisesti, mutta tämä vaatii huolellisuutta ja sitä, että poistettava tarjous ei ole "Viimeisin", eikä "Hyväksytty".

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
Siirrä työlistaan-painikkeella projektin tiedot viedään Työlista-välilehdelle.  Työlista-välilehdellä voidaan määritellä, aikataulu projektin kuormitukselle. Aikataulu määritellään viikkonumerolla, joka haetaan Tarjouslaskenta-välilehden Toimitusaika-solusta. Projektin voi merkitä Työlistassa aloitetuksi, valmiiksi,toimitetuksi tai myöhästyneeksi, tai vaihtoehtoisesti kun Lähete luodaan, Työlistasta haetaan Lähetteen projektinumeron perusteella sama projektinumero ja merkitään projektinumerolla olevat rivit automaattisesti aloitetuksi, valmiiksi ja toimitetuksi. Samalla Työlistaan viedään myös toteutunut toimitusaika.
Projektin työvaiheet menevät eri riveille, jotta työvaiheiden kuormitus pystytään jakamaan jokaiselle vaiheelle erikseen.
Kun tarjous viedään työlistaan, sovellus kysyy oletko vienyt viimeisimmän version tarjouslistaan. Tämä pitää tarkistaa, jotta työlistaan menevät oikeat tiedot. Tarjousta vietäessä työlistaan työlista käydään läpi duplikaattien varalta. Jos työlistassa on jo työ samalla projektinumerolla, työlistaan vienti perutaan automaattisesti.

[![Työlistaan vienti](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/VieTyoListaan.gif?raw=true "Työlistaan vienti")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/VieTyoListaan.gif?raw=true "Työlistaan vienti")

## PDF:n vienti
Tarjouksesta, tilausvahvistuksesta ja lähetteestä voidaan luoda PDF-tiedostot. PDF:n luonnille on olemassa omat PDF-vienti napit. Kun PDF tallennetaan haetaan sen tiedot kyseiseltä välilehdeltä, TarjousPDF:n tiedot haetaan Tarjous-välilehdeltä, TilausvahvistusPDF:n tiedot Tilausvahvistus-välilehdeltä ja LähetePDF:n Lähete-välilehdeltä . Tämä tarkoittaa sitä, että kun PDF luodaan, Tarjouslaskenta-välilehdellä voi olla eri tarjous kun välilehdellä, josta halutaan luoda PDF.

## Työkortti
Työkorttiin merkitään tehdyt tuntimäärät eri työvaiheille. Työvaiheita voi muokata mieleisekseen.
Kun Työkortti-painiketta painetaan, viedään sinne tarjouksen asiakkaan tiedot ja projektin numero ja nimi, sekä toimitusaika.
Tarjouksen nimikkeet lisätään osalistaan. Työlista on tarkoitettu tulostettavaksi ja työvaiheiden kestot on tarkoitus täyttää manuaalisesti.

## Quality of life
Päivämääräsoluja voi muuttaa kalenterinäkymässä kaksoisklikkaamalla kyseistä solua.

![Kalenterinäkymä.](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Kuvat/pvmClick.PNG "Kalenterinäkymä") 

Ctrl + Z näppäinyhdistelmällä pääsee kumoamaan viimeisimmät muutokset.

Tarjouslistan tietoja voi filtteröidä, jotta tietojen haku tai tarkistus on sujuvampaa. Filtteröinti tulee "nollata" aina käytön jälkeen, siten, että kaikki rivit ovat taas näkyvillä, jotta tietojen vieminen ja hakeminen toimii sujuvasti.

[![Filtterointi](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/Filtterointi.gif?raw=true "Filtterointi")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/Filtterointi.gif?raw=true "Filtterointi")
