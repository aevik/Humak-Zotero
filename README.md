# Humak-Zotero
Humanistisen ammattikorkeakoulun raporttien lähdeviitetyyli Zotero-yhteensopivana (https://www.zotero.org) CSL-tiedostona.

## Tiedoston käyttöönotto

Lataa itsellesi paikallinen kopio tiedostosta Humak-lähdeviitteet.csl (klikkaa yllä näkyvässä tiedostoluettelossa tiedoston nimeä hiiren oikealla painikkeella ja valitse "tallenna kohde levylle").

Avaa Zotero. Siirry kohtaan Muokkaa > Asetukset > Viitteet. Lisää tyyli käyttöön klikkaamalla tyyliluettelolistan alapuolella sijaitsevaa +-merkkiä. Valitse tiedosto ja klikkaa Avaa.

Tässä vaiheessa Zotero varoittaa, että tiedosto "ei ole kelvollinen CSL 1.0.2 -tyylitiedosto, joten se ei välttämättä toimi oikein Zotero:n kanssa. Haluatko jatkaa?". Valitse "OK" (ks. selitys varoitukseen alempaa).

Nyt tyylilistastasi löytyy "Humak - Humanistinen ammattikorkeakoulu (2023)" -niminen tyyli, jonka voit ottaa käyttöön muiden tyylien tapaan. Esimerkiksi Wordissa (edellyttäen, että olet asentanut siihen Zotero-laajennuksen) valitset käyttämästi viitetyylin valikosta kohdasta Zotero > Document Preferences.

## Virheilmoituksen syy

Tarkkaan ottaen tämä CSL-tiedoston ei käytä Zoteron CSL 1.0.2 -formaattia vaan sen CSL-M-laajennusta. Vaikka Zotero tiedostoa asennettaessa herjaakin virheestä, tiedosto toimii.

Syy ristiriitaan on siinä, että pelkkä CSL 1.0.2 -formaatti ei tarjoa mahdollisuutta siihen, että julkaisun päivämäärä kerrotaan vain, jos päivämäärä on ilmoitettu vuotta tarkemmin (jos taas annetun päivämäärän tarkkuus on ennalta vain vuosi, se toistetaan joka tapauksessa lähdeluettelorivin alussa tekijän perässä, joten täysin samaa tietoa ei kuulu toistaa myöhemmin). Lue lisää: https://forums.zotero.org/discussion/82784/csl-choose-if-date-part-day-is-not-null

## Kommentit ja kehitystoiveet

Lähetä viestiä osoitteeseen aatu.komsi@iki.fi.

Kaikenlainen testausapu auttaa, sillä Humakin viittausopas (https://humak.libguides.com/viittausopas/lahdeluettelo) on monilta yksityiskohdilta puutteellinen, ja minulla ei ole ollut aikaa syöttää omaan Zoterooni riittävästi kaikkia mahdollisia esimerkkilähteitä.

## Tuetut kielet ja lähteet

Nykyinen versio toimii luotettavasti vain suomeksi.

Se tukee seuraavia lähteitä
- Aikakausjulkaisun artikkeli
- Aikakauslehden artikkeli
- Blogikirjoitus
- Kirja
- Kirjan osa
- Opinnäytetyö
- Raportti
- Säädös
- Websivu

Lakipykälän osalta kirjaa lain nimi kenttään Laki (esim. "Kuntalaki"), lain numero kenttään Lakinumero (esim. "410/2015") ja mahdollinen pykälä kenttään Osio (esim. "22 §").

Aikakausjulkaisun artikkelin tai aikakauslehden artikkelin kohdalla kirjaa lehden nimi kenttään Julkaisu, Vuosikerta-kenttään lehden vuosikerran tai julkaisuvuoden numero (esim. 2015 tai 42) ja Numero-kenttää kyseisen lehden numero. Lisää julkaisupäivä kenttään Päiväys. (Mainittakoon, että Humakin ohjeet ovat puutteelliset sen suhteen, miten vuosikerta ja julkaisupäivä tulisi lähdeluettelossa ilmoittaa. Olen siis käyttänyt tulkintaani.)

Websivun kohdalla käytä kenttää Websivu kertoaksesi sivuston kattonimen. Tämän ei välttämättä kannata olla sama kuin sivuston otsikkorivi selaimessa, jos otsikko sisältää myös jonkinlaisen mainoslauseen, vaan ennemmin sama kuin organisaation nimi.

Opinnäytetyön (myös väitöskirja) osalta kirjoita oppilaitoksen nimi kenttään Yliopisto (esim. "Humanistinen ammattikorkeakoulu") ja tutkinnon nimi kenttään Tyyppi (esim. Järjestö- ja nuorisotyön koulutusohjelma. Opinnäytetyö (YAMK)").

Yleisesti ottaen kenttiin tulevien tekstien loppuun ei tule lisätä pistettä, vaan Zotero lisää ne automaattisesti tulostaessaan kentät lähdeluetteloon.

## Tiedossa olevat puutteet ja virheet

- Kirja, josta ei ole kirjattu Zoteroon muut kuin toimittajat, muotoutuu väärin lähdeluettelossa: toimittajien nimet tulevat vasta julkaisun nimen jälkeen. Tämä ei tosin liene käytännössä ongelma, sillä lähtökohtaisesti lähdettä käytettäessä on kuitenkin aina tiedossa itse tekstin kirjoittaja eikä vain toimittaja. (Vika ei koske kokonaan anonyymeja julkaisuja.)
- Jos julkaisun tekijä ei ole tiedossa ja siksi lähdeluettelon alussa kerrotaan julkaisuja eikä tekijä, julkaisijan kotipaikkaa mainita myöhemmin rivillä (en jostakin syystä onnistunut saamaan Zoteroa toistamaan julkaisijan nimeä enkä halunnut tekstiin ylimääräistä "Helsinki:" -tekstiä keskelle).
- Esitelmä-tyypissä kenttä Tapaamisen nimi (ts. esitelmän/luennon tilaisuuden nimi) ei tule mukaan lähdeluetteloon.
- Humakin lähdeviiteohjeiden mukaan julkaisun, jolla on vähintään kolme tekijää, kaikkien tekijöiden nimet mainitaan viitattaessa lähteeseen ensimmäistä kertaa, esim. "(Korhonen, Mattila & Vauranen 2023)", ja seuraavilla kerroilla samaan lähteeseen viitattaessa vain ensimmäisen nimen osalta ja "ym.", esim. "(Korhonen ym. 2023)". Nykyinen tyylitiedosto ei osaa tunnistaa, monettako kertaa samaan lähteeseen viitataan, vaan tuottaa aina vain "ym."-version. Nämä tekstit pitää siis korjata käsin.

Lähdeluetteloon ei myöskään liitetä vielä mainintoja esimerkiksi siitä, jos kirja on e-kirja tai äänikirja tai jos lähde ei julkaisematon. Humakin ohjeen mukaan tietysti kuuluisi.

(Syy puutteisiin johtuu siitä, että CSL-tiedoston spesifikaatio on erittäin epäselvä ja käyttää monia eri termejä kuin Zotero, joten oikeat kenttäviittaukset koodissa vaativat lisäselvityksiä.)
