---
---
Laddningstid
=========================

I denna rapporten så går jag igenom tre olika sidor där jag analyserar laddningstiden mellan olika hemsidor och kollar på vad som eventuellt kan förbättras eller om de faktiskt laddar tillräckligt snabbt.


Urval:
--------

Jag har valt ut tre stycken banker som jag ska analysera. Jag valde banker för att det är något som vi alla använder på, kanske en daglig basis. Det en förväntar sig av en banks hemsida är att den ska vara snabb och smidig, förutom att den ska vara säker såklart. Efter som att hemsidorna faller i samma kategori och fyller samma syfte, så bör de ju ha en liknande struktur och bör då ha en någorlunda liknande laddningstid.

Bankerna som jag har valt är:
###### SEB
[https://seb.se/](https://seb.se/)

###### Nordea
[https://www.nordea.se/](https://www.nordea.se/)

###### Swedbank
[https://www.swedbank.se/privat.html](https://www.swedbank.se/privat.html)

Metod
-------

Jag har använt mig utav DevTools i Firefox för att mäta laddningstid, antal filförfrågningar och storlek på sidan. Jag har gjort mätningarna på 3 stycken undersidor för hemsidorna och för varje undersida så har jag gjort mätningen 3 gånger för att ta fram ett medelvärde, som kan svara för ett rättvist resultat. Utöver DevTools så har jag änvänt [Googles PageSpeed](https://developers.google.com/speed/pagespeed/insights/), som är ett verktyg för att mäta laddningstiden på en hemsida, både för mobil och för dator. PageSpeed ger även tips på hur webbplatsen kan förbättras och betygsätter den från 0 till 100.

Resultat
----------

Mina mätningar går att hitta på [mitt google-kalkylark](https://docs.google.com/spreadsheets/d/10xvuMqnf5jyRCH5p1HVEMEYMoBcVDrrjDe6rRs3GUEc/edit?usp=sharing).

#### SEB

[FIGURE src=image/SEB.jpg?w=450]

Undersidor inkluderade i studien: [Startsida](https://seb.se/) [Bli Kund](https://seb.se/kundservice/kundservice-privat/bli-kund) [Företag](https://seb.se/foretag)

###### DevTools

Antal filförfrågningar: 37

Laddningstid: 3,09s

Nedladdningsstorlek: 2,21MB

###### Googles PageSpeed
Dator: 82/100

Mobil: 28/100

SEB fungerar bra för datorer, men när det kommer till mobiler så faller de ganska hårt. De hade kunnat komprimera både text och bilder bättre, även skippa en del fonts som inte verkar användas.

#### Nordea

[FIGURE src=image/nordea.jpg?w=450]

Undersidor inkluderade i studien: [Startsida](https://www.nordea.se/) [Bli Kund](https://www.nordea.se/privat/bli-bankkund/) [Företag](https://www.nordea.se/foretag/)

###### DevTools

Filförfrågningar: 50

Laddningstid: 6,34s

Nedladdningsstorlek: 1,3MB

###### Googles PageSpeed

Dator: 99,5/100

Mobil: 68/100

Nordea fungerar bra både på mobiler och på datorer, men snäppet sämre på mobiler. För att förbättra det, så hade de också kunnat komprimera bilderna bättre, det vill säga skicka dem i andra format.

#### Swedbank

[FIGURE src=image/swedbank.png?w=450]

Undersidor inkluderade i studien: [Startsida](https://www.swedbank.se/) [Bli Kund](https://www.swedbank.se/privat/kunderbjudanden.html) [Företag](https://www.swedbank.se/foretag.html)

###### DevTools

Filförfrågningar: 42

Laddningstid: 2,74s

Nedladdningsstorlek: 1,58MB

###### Googles PageSpeed

Dator: 96/100

Mobil: 11/100

Swedbank fungerar också bra på datorer, men helt fruktansvärt när det gäller mobiler. En sak som hade hjälpt webbplatsen mycket är att komprimera texten. Utöver det så har de några grejer som blockerar renderingen, vilket kan tas bort.

Bäst resultat
--------

Nordea hamnar på första plats. De har den stabilaste webbplatsen, den fungerar bra för både datorer och mobiler. De har minst nedladdningsstorlek utav dem här webbplatserna.

Swedbank kommer kämpar sig upp på andra plats, trots de dåliga resultaten för mobiler. De hade snabbast laddningstid enligt mina mätningar i DevTools och en ganska låg nedladdningsstorlek.

Sist hamnar då SEB, som har störst nedladdningsstorlek och presterar varken jättebra på datorer, men speciellt inte på mobiler.

Analys
--------

Jag tycker ändå att de här webbplatserna möter upp mina förväntningar på vad jag förväntar mig av en bank. De laddar i mitt tycke snabbt och fungerar stabilt. Visst de hade mycket problem med att ladda bra för mobilt bruk, vilket inte är okej idag, när de flesta gör sina bankärenden i mobilen. Men i deras försvar så använder banker sig utav appar som är tillägnade till mobiler, vilket jag tror är en bra förklaring till de dåliga resultaten för mobiler.

De verkar vara svaga på ungefär samma punkter. Bland annat textkomprimering är en sak som de alla borde jobba på. Det är något som jag själv inte har tänkt på kan slöa ner laddningstiden så mycket, men det verkar vara den gemensamma akilleshälen.

Jag tycker att så länge en sida laddar på under 5 sekunder så känns det snabbt och om det går över 10 sekunder så börjar det kännas lite långsamt, rent generellt i alla fall. Men det är beroende på syftet av sidan. Vissa sidor behöver ha en snabbare laddningstid och för vissa så märks det inte av lika mycket om de är lite långsammare. Jag tycker i alla fall att samtliga banker i mina mätningar har upplevts som snabba.

Referenser
-----------

[https://seb.se/](https://seb.se/)

[https://seb.se/kundservice/kundservice-privat/bli-kund](https://seb.se/kundservice/kundservice-privat/bli-kund)

[https://seb.se/foretag](https://seb.se/foretag)

[https://www.nordea.se/](https://www.nordea.se/)

[https://www.nordea.se/privat/bli-bankkund/](https://www.nordea.se/privat/bli-bankkund/)

[https://www.nordea.se/foretag/](https://www.nordea.se/foretag/)

[https://www.swedbank.se/](https://www.swedbank.se/)

[https://www.swedbank.se/privat/kunderbjudanden.html](https://www.swedbank.se/privat/kunderbjudanden.html)

[https://www.swedbank.se/foretag.html](https://www.swedbank.se/foretag.html)


[https://docs.google.com/spreadsheets/d/10xvuMqnf5jyRCH5p1HVEMEYMoBcVDrrjDe6rRs3GUEc/edit?usp=sharing](https://docs.google.com/spreadsheets/d/10xvuMqnf5jyRCH5p1HVEMEYMoBcVDrrjDe6rRs3GUEc/edit?usp=sharing)

[https://developers.google.com/speed/pagespeed/insights/](https://developers.google.com/speed/pagespeed/insights/)
Övrigt
--------

Rapport av Henrik Lindeborg
