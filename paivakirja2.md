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