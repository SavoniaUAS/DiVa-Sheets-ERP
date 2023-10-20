# Toiminnanohjausjärjestelmän käyttöohjeet
## Yleistä
Järjestelmän keskeiset toiminnot löytyvät Tarjouslaskenta-välilehdeltä. Sarakkeiden otsikoita ja värejä voi muuttaa. Listoissa odotetaan että listat jatkuvat saman muotoisina käytännössä loputtomasti alaspäin jatkuvina riveinä. Tämän vuoksi älä vaihda sarakkeiden paikkoja, sillä sovelluslogiikka odottaa tiettyjen sarakkeiden ja rivien pysyvän paikoillaan. Tämä koskee kaikkia välilehtiä. Sarakkeita voi halutessaan värittää ja kuvia voi lisätä. Jos välttämättä haluat muuttaa sovelluksen ulkoasua, piilota haluamasi sarakkeet pois näkyvistä.

## Käyttöönoton valmistelu
Käy läpi järjestelmän välilehdet ja kokeile kuinka ne toimivat. Voit käyttöönoton päätteeksi poistaa Tarjouslista-, Työlista- ja Asiakaslista-välilehdiltä esimerkkitiedot sekä vaihtaa Yritystiedot-välilehdelle oman yrityksesi tiedot. 

Määrittele hinnoittelu työvaiheille tuntihinnat-välilehdellä ja kapasiteetit työviikoille kapasiteetti-välilehdelle.

Voit muuttaa otsikoita kuvaamaan paremmin työvaiheita ja käyttötarpeita.
 
## Välilehdet
#### Tarjouslaskenta
Täytä tarjouslaskentaan tarjottavat tuotteet, niiden määrät ja  allekkaisille riveille. Älä jätä tyhjiä rivejä. Tarjouslaskennan rivejä täytettäessä hinnat käydään hakemassa vastaavan työvaiheen perusteella Tuntihinnat-välilehdeltä (Esim. Tarjouslaskennan Työvaihe_1 vastaa Tuntihinnat-välilehden Työvaihe_1-saraketta.). Materiaalin ja käsittelyn hinta määritellään tarjouslaskentaan itse. <strong>Muista syöttää projektinumero, projektin nimi ja asiakkaan viite, sekä määritellä toimitusaika aina uutta projektia luodessa</strong>. Kun tarjouslistasta haetaan tietoja tarjouslaskenta-välilehdelle nämä kohdat täyttyvät automaattisesti.

Tarjouslaskenta-välilehden sarakkeet Työhinta, Yhteensä, Yhteensä+kate ja Hinta/Kpl ovat automaattisesti laskettuja.

Napit ovat:
- Hae asiakas - Hae asiakkaan tiedot tarjouslaskenta-välilehdelle asiakaslista-välilehdellä olevan yrityksen nimen perusteella.
- Tyhjennä - Tyhjennä tarjouslaskenta-välilehden tiedot.
- Aseta muotoilu - Asettaa johdonmukaisen muotoilun tarjouslaskenta-välilehden riveille.
- Hae tarjouslistasta - Hae tarjous projektinumeron perusteella.
- Luo tarjous - Luo tarjouslaskentaan syötetyistä riveistä tarjous.
- Siirrä tarjouslistaan - Hae tarjous muokattavaksi tarjouslista-välilehdeltä projektinumeron perusteella.
- Luo tilausvahvistus - Luo tarjouslaskennan riveistä tilausvahvistus. 
- Siirrä työlistaan - Siirrä tarjouslaskennan rivit työlistaan. Vaatii, että tarjouslaskennan uusin versio löytyy tarjouslistasta.
- Luo lähete - Luo tarjouslaskenta-välilehdelle ladatuista tiedoista lähete tulostettavaksi.
- Luo työkortti - Luo tarjouslaskenta-välilehdelle ladatuista tiedoista työkortti tulostettavaksi.
- Tarjous PDF - Luo tarjouslaskentaan ladatusta listasta pdf-tiedosto tarjoukseksi.
- Lähete PDF - Luo tarjouslaskentaan ladatusta listasta pdf-tiedosto lähetteeksi. 
- Tilausvahvistus PDF - Luo tarjouslaskentaan ladatusta listasta pdf-tiedosto tilausvahvistukseksi.

#### Tarjouslista
Tarjouslista toimii ohjelman tietokantana. Tarjouslaskenta-välilehdellä määritellyt tiedot viedään tarjouslistan alimmaiseksi ja tarjouksen rivien "Viimeisin" sarakkeen valintaruudut merkitään automaattisesti. "Viimeisin"-sarakkeen valintaruutua käytetään siihen, että tarjouslistasta osataan tuoda tarjouksen viimeisin versio. Täällä tarjous on tallessa sillä välin kun tarjous lähetetään asiakkaalle ja saadaan sille hyväksyntä. Jos tarjousta halutaan myöhemmin muokata, sen voi hakea tarjouslistasta. Samalla ”Viimeisin” sarakkeen valintaruudun merkinnät otetaan automaattisesti pois vanhasta versiosta.
<strong>Kun tarjousta on muokattu, pitää tarjous lisätä uudestaan tarjouslistaan Siirrä tarjouslistaan-painikkeella, jolloin muokatusta tarjouksesta tulee uusi ”Viimeisin” tarjous</strong>. Myös vanha tarjous jää tarjouslistaan, jos sitä halutaan tarkastella myöhemmin. Vanhoja tarjouksia voi halutessaan poistaa myös manuaalisesti, mutta tämä vaatii huolellisuutta ja sitä, että poistettava tarjous ei ole "Viimeisin", eikä "Hyväksytty" toimivuuden takaamiseksi.

#### Tarjous
Tarjoukseen ladataan tarjouslaskennasta tulostettavaan pohjaan tarjouksen tiedot. Vaatii, että yrityksen tiedot on täytetty yritystiedot-välilehdelle

#### Työlista
Työlista-välilehdellä voidaan määritellä, aikataulu projektin kuormitukselle. Aikataulu määritellään viikkonumerolla, joka haetaan Tarjouslaskenta-välilehden Toimitusaika-solusta. Projektin voi halutessaan merkitä työlistassa aloitetuksi, valmiiksi,toimitetuksi tai myöhästyneeksi projektin etenemisen mukaan. Vaihtoehtoisesti kun Lähete luodaan, työlistasta haetaan lähetteen projektinumeron perusteella saman projektinumeron rivit ja merkitään automaattisesti aloitettu- , valmis-  ja toimitettu-valintaruudut. Samalla työlistaan viedään myös toteutunut toimitusaika.
Projektin työvaiheet menevät eri riveille, jotta työvaiheiden kuormitus pystytään jakamaan jokaiselle vaiheelle erikseen viikkokohtaisesti.

Kun tarjous viedään työlistaan, sovellus kysyy oletko vienyt viimeisimmän version tarjouslistaan. Tämä pitää tarkistaa, jotta työlistaan menevät oikeat tiedot. Tarjousta vietäessä työlistaan työlista käydään läpi duplikaattien varalta. Jos työlistassa on jo työ samalla projektinumerolla, työlistaan vienti perutaan automaattisesti.

#### Tilausvahvistus
Tilausvahvistus-välilehdelle ladataan tarjouksen tiedot tarjouslaskenta-välilehdeltä. Kun tarjous viedään Tilausvahvistus-välilehdelle, sovellus käy merkitsemässä automattisesti tarjouslistasta "Hyväksytty"-valintaruudun ja kysyy onko tuotanto ajoitettu. 
Vaatii, että yrityksen tiedot on täytetty yritystiedot-välilehdelle.

#### Lähete
Lähete-välilehti ladataan tarjouksen tiedot tarjouslaskenta-välilehdeltä. Lähetettä tehdessä tietojen on oltava työlistassa, koska viimeistään tässä vaiheessa työlistan valintaruudut käydään automaattisesti merkitsemässä, pl. Myöhässä-valintaruutu.
Vaatii, että yrityksen tiedot on täytetty yritystiedot-välilehdelle.

#### Työkortti
Työkortti toimii tuotannon työntekijöille työkorttina, jossa kerrotaan mitä tulee tehdä. Ei ole pakko käyttää, jos tuotanto ei tarvitse erikseen työkortteja.

#### Asiakaslista
Asiakaslista toimii yksinkertaisena asiakastietokantana, josta voidaan hakea tarjouslaskenta-välilehdelle asiakkaan tiedot. Asiakkaiden tietoja voi muuttaa, ja listaan voi lisätä rivejä. Lista ei saa sisältää tyhiä rivejä asiakkaiden välillä.

#### Kapasiteetti
Kapasiteetti-välilehdellä määritellään eri työpisteillä käytössä olevaa kapasiteettia viikkotasolla. Yksittäiselle työvaiheelle käytössä oleva kapasiteetti kuvataan kahdella sarakkeella: Viikkonumero ja viikon kapasiteetti tunteina. Kapasiteetin ollessa viikkokohtainen, sillä ei voi käsitellä yksittäisten työpäivien kapasiteettia.

#### Tuntihinnat
Tuntihinnat välilehdellä määritellään eri työvaiheiden hinnat. Määrittele itse omien työvaiheidesi tuntihinnat. Tuntihinnat-välilehdellä olevat työvaiheet vastaavat Tarjouslaskenta-välilehdellä olevia työvaiheita.

#### Yritystiedot
Aseta oman yrityksesi tiedot sekä toimitusehdot tälle välilehdelle niille varatuille paikoille. Tiedot haetaan täältä automaattisesti tarjoukseen, lähetteeseen sekä tilausvahvistukseen.

## Ohjeet

### Asiakasrivien täyttö
Asiakaslista-välilehdelle pystytään lisäämään asiakkaan tiedot. Yhden asiakkaan tiedot lisätään yhdelle riville. Asiakkaat täytyy lisätä riveille, niin ettei asiakaslistaan muodostu tyhjiä rivejä. Jos lista sisältää tyhiä rivejä asiakkaiden välillä, asiakkaiden hakeminen ei onnistu.

:white_check_mark:
![Asiakaslistan täyttö.](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Kuvat/AsiakasListaOikein.PNG "Asiakaslista oikein") 


:x:
![Asiakaslistan täyttö.](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Kuvat/AsiakasListaVaarin.PNG "Asiakaslista vaarin") 

### Asiakkaan hakeminen
Kun asiakaslistaan on lisätty asiakkaita, voidaaan niitä hakea tarjouslaskenta-välilehdelle.

[![Asiakkaan lisäys](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/AsiakkaanHakeminen.gif?raw=true "Asiakkaan hakeminen")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/AsennusGif.gif?raw=true "Asiakkaan hakeminen")

### Tarjouslaskennan rivien täyttäminen
Laskutoimituksiin käytetyt kaavat on upotettu harmaalla värjättyihin soluihin, joten soluja ei saa mennä muuttamaan. 
Sovellus ei hyväksy tyhjiä rivejä tarjouslaskennan rivejä täytettäessä. 
Jos solu taas jää tyhjäksi, sen arvoksi lisätään 0, kun tarjous viedään tarjouslistaan.

:white_check_mark:
![Tarjouslaskenta täyttö oikein.](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Kuvat/Tarjouslaskenta_taytto-Oikein.PNG "Tarjouslaskenta täyttö oikein") 


:x:
![Tarjouslaskenta täyttö väärin.](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Kuvat/Tarjouslaskenta_taytto-Vaarin.PNG "Tarjouslaskenta täyttö väärin") 

### Päivämäärät
Päivämäärät pitää olla muodossa YYYY/MM/DD eli vuosi/kuukausi/päivä. Tarjouksen päivämäärän sovellus luo automaattisesti. Toimitusaika muunnetaan automaattisesti tarjouslistassa viikkonumeroksi.

### Tarjouslista
Siirrä tarjouslistaan-painiketta painamalla, tarjouslaskenta-välilehdelle syötetyt rivit viedään tarjouslistaan ja merkitään tarjouslistassa viimeisimmäksi versioksi. Muista määritellä projektinumero, projektinimi, asiakkaan viite ja toimitusaika kun luot uutta projektia.

[![Tarjouslistaan vienti](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/SiirtoTarjouslistaan.gif?raw=true "Tarjouslistaan vienti")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/SiirtoTarjouslistaan.gif?raw=true "Tarjouslistaan vienti")

### Luo tarjous, tilausvahvistus ja lähete
#### Tarjous
Tarjous luodaan painamalla Luo Tarjous-painiketta, jolloin tarjous-välilehdelle viedään tarjouslaskenta-välilehdellä olevan projektin tiedot

[![Tarjous](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoTarjous.gif?raw=true "Tarjouslistaan vienti")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoTarjous.gif?raw=true "Tarjous")

#### Tilausvahvistus
Tilausvahvistus luodaan painamalla Luo Tilausvahvistus-painiketta, jolloin tilausvahvistus-välilehdelle viedään tarjouslaskenta-välilehdellä olevan projektin tiedot. Projekti merkitään hyväksytyksi tarjouslistassa.

[![Tilausvahvistus](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoTilausvahvistus.gif?raw=true "Tilausvahvistus")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoTilausvahvistus.gif?raw=true "Tilausvahvistus")

#### Lähete
Kun tarjouksen kaikki työvaiheet on valmiita voidaan tarjouksen tiedot viedä Lähete-välilehdelle painamalla Luo Lähete-painiketta, jolloin lähete-välilehdelle viedään tarjouslaskenta-välilehdellä olevan projektin tiedot. Projekti merkitään työlistassa aloitetuksi, valmiiksi ja toimitetuksi.

[![Lähete](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoLähete.gif?raw=true "Lähete")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/LuoLähete.gif?raw=true "Lähete")

### Työlista
Luo tilausvahvistus-painiketta painamalla tarjouslaskenta-välilehdellä olevat projektin tiedot viedään työlistaan. Työlistassa voidaan kuormittaa työn vaiheet halutuille viikoille ja määritellä, missä vaiheessa projekti on. Projekti merkitään työlistassa aloitetuksi, valmiiksi ja toimitetuksi viimeistään silloin kun lähete luodaan.

[![Työlistaan vienti](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/VieTyoListaan.gif?raw=true "Työlistaan vienti")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/VieTyoListaan.gif?raw=true "Työlistaan vienti")

### PDF:n vienti
Tarjouksesta, tilausvahvistuksesta ja lähetteestä voidaan luoda PDF-tiedostot. PDF:n luonnille on olemassa omat PDF-vienti napit. Kun PDF tallennetaan haetaan sen tiedot kyseiseltä välilehdeltä, TarjousPDF:n tiedot haetaan Tarjous-välilehdeltä, TilausvahvistusPDF:n tiedot Tilausvahvistus-välilehdeltä ja LähetePDF:n Lähete-välilehdeltä . Tämä tarkoittaa sitä, että kun PDF luodaan, Tarjouslaskenta-välilehdellä voi olla eri tarjous kun välilehdellä, josta halutaan luoda PDF. Tämän takia on hyvä tarkistaa, mistä tiedoista on PDF-tiedostoa tekemässä.
PDF-kansiopolku on Asiakkaat-pääkansio -> Yrityksen nimi-kansio -> Projektinumero-kansio ->  PDF-tiedostot.

[![PDF:n luonti](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/PDF-luonti.gif?raw=true "Lähete")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/PDF-luonti.gif?raw=true "PDF:n luonti")

### Quality of life
Päivämääräsoluja voi muuttaa kalenterinäkymässä kaksoisklikkaamalla kyseistä solua.

![Kalenterinäkymä.](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Kuvat/pvmClick.PNG "Kalenterinäkymä") 

Ctrl + Z näppäinyhdistelmällä pääsee kumoamaan viimeisimmät muutokset ja Ctrl + Y näppäinyhdistelmällä pääsee viimeisimpiin muutoksiin.

Tarjouslistan tietoja voi filtteröidä, jotta tietojen haku tai tarkistus on sujuvampaa. Filtteröinti tulee "nollata" aina käytön jälkeen, siten, että kaikki rivit ovat taas näkyvillä, jotta tietojen vieminen ja hakeminen toimii sujuvasti.

[![Filtterointi](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/Filtterointi.gif?raw=true "Filtterointi")](https://github.com/SavoniaUAS/DiVa-Sheets-ERP/blob/main/Gifs/Käyttöohje/Filtterointi.gif?raw=true "Filtterointi")
