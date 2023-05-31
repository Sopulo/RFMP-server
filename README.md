
# Miten luoda Ravenfield Multiplayer -palvelin

Tämän ohjeen avulla voit luoda toimivan Ravenfield Multiplayer -palvelimen käyttäen Windows tietokonetta.

Mitä tarvitset?

- Tietokone: Windows (10 tai 11)
- Ravenfield Multiplayer Mod (hankittu Steamista)
- Lähiverkon johon tietokone on liitetty
- Käyttäjätunnukset lähiverkon palomuurihallintaan ja tietokoneeseen
## Ohjeet, vaihe vaiheelta:

1 Kirjaudu sisään tietokoneellesi.

2 Paina seuraavia näppäimiä samaan aikaan: Windows(näppäin) + R. Varmista, että sinulla ei ole käytössa VPN palvelua tai muuta vastaavaa.

3 Kirjoita
```bash
  cmd
```
äsken auenneeseen kenttään ja paina ENTER-näppäintä.

4 Kirjoita
```bash
  ipconfig
```
äsken auenneeseen komentokehoitteeseen ja paina ENTER-näppäintä.

5 Etsi komentokehoitteeseen ilmestyneestä tekstistä oma paikallinen (jos tietokoneesi on yhdistetty lähiverkkoon langallisesti, löytyy IPv4-osoite otstikon "Ethernet adapter" alta) IPv4-osoitteesi kohadsta IPv4 Address. Se alkaa usein seuraavilla numeroilla: 192.168 ...

6 Omasta IPv4-osoitteestasi alempana on Default Gateway -niminen kohta. Sen vieressä oikealla puolella on useimmiten paikallisen verkkosi reitittimesi IP-osoite. Se saattaa olla esim. 192.168.1.1 tai 192.168.0.1 .

7 Avaa jokin tietokoneellesi asennetuista selainohjelmista. Navigoi kursorillasi hakupalkkiin ja kirjoita sinne reitittimesi IP-osoite. Paina ENTER-näppäintä.

8 Kirjaudu sisään reitittimeesi.

9 Mene Port Fowarding -kohtaan reitittimesi hallintapaneelissa. Huom. jokainen reititin on erilainen. Lue tarvittaessa oman reittimesi ohjekirja jos kohtaat ongelmia.

10 Luo uusi porttiohjaus. Syötä porttinumeroksi portti 7777. Valitse protokollaksi kaikki/molemmat (all). Syötä oma paikallinen paikallisen IPv4-osoite kohtaan jossa määritellään paikallisen laitteen IP-osoite.

11 Tallenna muutokset ja kirjaudu ulos reitittimesi hallintapaneelista.

12 Avaa Steam -aplikaatio tietokonneellasi. Mene kohtaan kauppa. Kirjoita "Hae" -palkkiin

```bash
  Ravenfield: Multiplayer Mod
```
. Tämän jälkeen napauta ehdotettua peliä ja sitten Pelaa Nyt -painiketta.

13 Pienennä Ravenfield Multiplayer Mod -ikkuna ja siirry työpöydällesi.

14 Paina seuraavia näppäimiä samaan aikaan: Windows(näppäin) + R. 

15 Kirjoita auenneeseen kenttään
```bash
  taskmgr
```
ja paina ENTER-näppäintä.

16 Avaa tarvittaessa valikko napauttamalla kolmea viivaa oikeasta yläkulmasta.

17 Mene kohtaan Prosessit. Etsi sieltä prosessi nimeltä Ravenfield Miltiplayer.exe. Laajenna prosessi sen nimestä vasemmalla puolella olevasta liukuvalikon merkistä.

18 Näkyviin tulee kaksi uutta prosessia. Paina oikealla korvalla nyt uutta esiin tullutta prosessia Ravenfield Multiplayer.exe.

19 Valitse auenneesta valikosta ominaisuudet. Ominaisuus ikkunassa oikeaklikkaa Sijainti: -kohdan oikealla puolella olevaa polkua. Napauta valitse kaikki. Tämän jälkeen oikeaklikkaa uudelleen Sijainti: -kohdan oikealla puolella olevaa polkua ja valitse kopioi.

20 Avaa pikavalikko painamalla Windows-näppäintä. Kirjoita

```bash
  Windows defenderin palomuuri
```
ja paina ENTER-näppäintä.

21 Paina auenneen ikkunan vasemmassa laidassa olevaa Lisäasetukset -kohtaa.

22 Valitse auenneen ikkunan vasemmasta laidasta Saapuvan liikenteen säännöt. 

23 Valitse ikkunan oikeassa laidassa otsikon "Toiminnot" alta kohta "Uusi sääntö".

24 Suorita seuraavat asiat Säännön lisääminen -ikkunassa:

- Valite kohdasta "Säännön tyyppi:" vaihtoehto "Ohjelma"
- Paina "Seuraava >"
- Valitse kohta "Ohjelman polku"
- Paina kohdan "Ohjelman polku:" painiketta "Selaa..."
- Paina uuden ilmestyneen ikkunan ylälaidassa olevaa pitkää palkkia jossa näkyy tämänhetkinen tiedostopolku
- Oikeaklikkaa sinisellä maalautunutta tekstiä
- Valitse "Liitä" -kohta ja paina ENTER-näppäintä
- Napauta "Ravenfield Multiplayer.exe" -kohtaa
- Napauta "Avaa" -painiketta ikkunan alakulmasta
- Paina "Seuraava >"
- Valitse "Salli yhteys"
- Valitse "Mitä täämä sääntö koskee?" -kohdasta kaikki mahdolliset vaihtoehdot
- Paina "Seruraava >"
- Paina "Valmis"

25 Valitse auenneen ikkunan vasemmasta laidasta Lähtevän liikenteen säännöt.

26 Valitse ikkunan oikeassa laidassa otsikon "Toiminnot" alta kohta "Uusi sääntö".

27 Suorita seuraavat asiat Säännön lisääminen -ikkunassa:

- Valite kohdasta "Säännön tyyppi:" vaihtoehto "Ohjelma"
- Paina "Seuraava >"
- Valitse kohta "Ohjelman polku"
- Paina kohdan "Ohjelman polku:" painiketta "Selaa..."
- Paina uuden ilmestyneen ikkunan ylälaidassa olevaa pitkää palkkia jossa näkyy tämänhetkinen tiedostopolku
- Oikeaklikkaa sinisellä maalautunutta tekstiä
- Valitse "Liitä" -kohta ja paina ENTER-näppäintä
- Napauta "Ravenfield Multiplayer.exe" -kohtaa
- Napauta "Avaa" -painiketta ikkunan alakulmasta
- Paina "Seuraava >"
- Valitse "Salli yhteys"
- Valitse "Mitä täämä sääntö koskee?" -kohdasta kaikki mahdolliset vaihtoehdot
- Paina "Seruraava >"
- Paina "Valmis"

28 Käynnistä tietokoneesi uudelleen.

29 Avaa Steam -aplikaatio tietokonneellasi. Mene kohtaan kauppa. Kirjoita "Hae" -palkkiin

```bash
  Ravenfield: Multiplayer Mod
```
. Tämän jälkeen napauta ehdotettua peliä ja sitten Pelaa Nyt -painiketta.

30 Paina pitkään "Play" -painiketta jonka näet "Ravenfield Multiplayer Mod" -pelin kotinäkymässä. Paina ESC-näppäintä. Aseta haluamasi valinnat palvelimen luontivalikoihin ja paina "Create" -painiketta.

Onneksi olkoon! Olet luonut "Ravenfield Multiplayer Mod" -palvelimen.
