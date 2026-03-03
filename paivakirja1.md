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