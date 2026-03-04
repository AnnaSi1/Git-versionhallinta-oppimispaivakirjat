# Git-versionhallinnan oppimispäiväkirjat
Oppimispäiväkirjat

# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Aluksi oli vaikeaa, kun käytin gittiä vscoden terminaalia, ja komennot eivät toimineet siinä. Sitten muistin, että pitää avata git bash, ja sillä komennot alkoivat toimimaan. 

Helppoa oli perus addin ja commitin käyttö, koska niitä olen käyttänyt aiemminkin koulutehtävissä. Enemmän haasteita aiheutti peruuttaminen ja revert, niitä olen käyttänyt vähemmän. Hankala on muistaa, missä tilanteessa käyttää mitäkin toimintoa. Myös en aluksi käyttänyt revertin yhteydessä talletuksen koodia, mutta tähän löytyi helposti ratkaisu materiaaleista. 

Minua auttoi oppimaan ja selvitti esteet, että kertasin materiaaleja uudelleen. Myös se auttoi, että googletin lisätietoja komentojen käyttämisestä.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| cd | siirtyy kansiorakenteessa |
| init | perustaa repositorion hakemistoon, joka ei ole vielä versionhallinnassa |
| cd .. | siirtyy kansiorakenteessa ylemmäs |
| git status | näyttää tiedostojen tilan |
| git add | merkitään otettavaksi mukaan seuraavaan talletukseen |
| git commit | talletetaan |
| rm | poistaa tiedoston |
| git log | näyttää commit-talletusten historian |
| git tag | lisää tagin |
| git reset | peruuttaa lisäyksen |
| git restore | palauttaa tiedoston versionhallinnan tuoreimman version tasalle, jos muutoksia ei ole vielä talletettu versiohallintaan |
| git revert | peruuttaa viimeisen talletuksen |

# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Haarojen ja paikallisen ja etärepositoryn ymmärtäminen on vähän hankalaa. Oppimateriaalin kuvat olivat hyviä ja selkeyttivät tilannetta. Minulla oli erityisesti hankaluuksia aluksi saada etärepositorio yhditymään paikalliseen haaraan (koska olin kirjoittanut osoitteen väärin) ja toisaalta saada etärepositoryssa tehdyt muutokset paikallisiksi. 

Oppimateriaalin ohjeet ovat hyvä ja seikkaperäiset, joten ne auttavat. Myös kysyin tekoälyä selittämään minulle jonkin ilmoituksen jonka sain, se auttoi ymmärtämään asiaa. 

Helppoa oli paikallisten haarojen yhdistäminen, koska sitä olen tehnyt aiemminkin. 

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| mv | Muuttaa tiedoston nimen |
| switch | Vaihtaa haaraa |
| switch -c haarannimi | Luo uuden haaran ja vaihtaa siihen |
| git checkout | Vaihtaa haaraa |
| git merge --no-ff | Yhdistää haarat, mutta ei mahdollista nopeaa yhdistämistä, eli yhdistämisestä jää jälki |
| git remote add | lisää paikallisen repositoryn etärepositorioon |
| git remote -v | Näyttää etärepositoryn tiedot |
| git push | Siirtää paikalliset tiedot etärepositoryyn |
| git fetch | Näyttää etärepositoryn tiedot |
| git pull | Näyttää ja yhdistää etärepositoryn tiedot paikalliseen repositoryyn (fetch + merge)|

# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Siitä on hyötyä, että voin tarvittaessa palata vanhoihin versioihin ja näen, mitä on missäkin kohdassa muutettu. Myös haaroista on apua myös yksin kehittämisessä, koska esimerkiksi jotain toiminnallisuutta voi kokeilla toisessa haarassa, ja jos ei toimi, alkuperäinen sovellus päähaarassa säilyy kunnossa.

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Useiden kehittäen projekteissa siitä on erityisesti hyötyä. Kommenttien avulla voi kommunikoida muille kehittäjille, miksi jotain on tehty jollain tavalla. Haarat ovat tässä erityisen hyödyllisiä, koska eri henkilöt pystyvät tekemään kehitystä samaan aikaan omissa haaroissaan.

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Ohjelmiston kehitys tehdään develop-haarassa. Jokainen kehittäjä tekee omat muutoksensa omassa haarassa, josta muutokset viedään develop-haaraan. Kaikkiin commiteihin kirjoitetaan kuvaavat kuvaukset, jotta projektikaverit tietävät mitä muutoksia missäkin on tehty. Testaa aina, että kaikki toimii, ennen kuin viet muutokset develop-haaraan. Developista mainiin siirretään vain valmiit tuotokset.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Erittäin hyödyllinen opintojakso. Konkreettiset tehtävät olivat todella hyvä tapa oppia. Ainut mitä kaipaisin enemmän, olisi vielä yksityiskohtaisempi ohje, miten konflikteja ratkotaan.