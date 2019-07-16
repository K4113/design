---
---
Sveriges tre största mobiloperatörer
=======================

I denna rapport ska jag analysera Sveriges tre största mobiloperatörer.
Aspekterna jag har valt att undersöka är:

- Typografi
- Färgschema
- Laddningstid
- Designprinciper

Jag kommer enbart att analysera startsidan för mobiloperatörernas hemsidor. Målet är att få fram aktuella trender inom webbplatsdesign.


Urval
-----------------------

Enligt [konkurrensverkets rapport från 2016](http://www.konkurrensverket.se/globalassets/publikationer/rapporter/rapport_2018-1_kap6-marknaden-for-mobiltelefoni.pdf) är de tre mobiloperatörer med flest marknadsandelar i Sverige Telia, Tele2 och Telenor.

Metod
-----------------------

Jag använder följande verktyg och hjälpmedel:

- [Google PageSpeed](https://developers.google.com/speed/)
- [Adobe Color](https://color.adobe.com/sv/)
- ColorZilla
- Inbyggda utvecklarverktygen som finns i Google Chrome.

Telia
-----------------------
[FIGURE src=image/mobile-operators/telia.PNG?w=300"]

**Typografi** -
Telia använder två olika sans-serif fonter. Pebble för de viktigaste budskapen och Helvetica Neu för övrigt. Jag är lite osäker på om Pebble är en etablerad font eller om den är utvecklad av dem själva. En annan iakttagelse är att Pebble alltid används tillsammans med versaler.

**Färgschema** -
Analogt färgschema med mycket lila som utgångspunkt. Färgerna skapar en känsla av lojalitet.
[FIGURE src=image/mobile-operators/fargschema-telia.PNG?w=300"]

**Laddningstid** -
Efter 11 omladdningar får jag medianvärdet 1.83 s. 1.9 mb laddas ner och de största filerna är en bild på 421 kb och en css fil på 243 kb

1.38, 1.52, 1.54, 1.73, 1.78, **1.83**, 1.84, 1.88, 1.89, 1.95, 1.96

Inte helt förvånande säger Google PageSpeed att de två största tidsbesparingarna vore "Skicka bilder i modernare bildformat" och "Skjut upp inläsningen av bilder som inte visas på skärmen". På fjärde plats kommer att ta bort oanvänd CSS.

**Designprinciper** -
Telia jobbar mycket med linjer, både horisontellt och vertikalt. Det känns väldigt grid-baserat med god balans. Om man använder huvudmenyn så finns lite lite rörelser på hemsidan. I övrigt finns det också knappar och länkar som "tänds" upp när man håller över dem som skapar lite liv på sidan. Den funkar väl i mobilt läge, men är bättre från datorn.

Tele2
-----------------------
[FIGURE src=image/mobile-operators/tele2.PNG?w=300"]

**Typografi** -
Tele2 har också enbart sans-serif fonter. På startsidan hittar jag Tele2Sans-Regular, Tele2Sans-Medium, Tele2Sans-Light och Tele2Slab-TextBold. Samtliga fonter är egenutvecklade utom i footern där man bara säger "sans-serif" och låter webbläsaren välja font.

**Färgschema** -
Otydligt färgschema. Eventuellt monokromatiskt färgschema eller analogt färgschema. Väldigt mörka fäger vilket skapar en "business" känsla. Orange är en relativt tydlig accentfärg.
[FIGURE src=image/mobile-operators/fargschema-tele2.PNG?w=300"]

**Laddningstid** -
Efter 11 omladdningar får jag medianvärdet 0.81 s och 0.86 mb laddas ner. Största bilden är 172 kb.

0.46, 0.47, 0.49, 0.50, 0.52, **0.81**, 0.83, 0.84, 0.84, 0.87, 0.89

Google PageSpeed ger Tele2 ett relativt bra betyg. Men man tycker att det går att förbättra bilderna ytterligare.

**Designprinciper** -
Mycket av startsidan består av stora bilder. Rörelser finns i huvudmenyn och knappar tänds upp när man håller över dem. Vissa delar är snyggt grid-baserat med balans. Men jag har väldigt svårt att förstå designen på bilden nedan. Osäker på om det är ett medvetet val eller inte. Tycker inte det ser speciellt bra ut i alla fall.
[FIGURE src=image/mobile-operators/design-tele2.PNG?w=300"]

Telenor
-----------------------
[FIGURE src=image/mobile-operators/telenor.PNG?w=300"]

**Typografi** -
På Telenors startsida används framförallt en font som heter Roboto. Den är utvecklad av google och är en sans-serif font. På några enstaka ställen finns även en font som heter telenorlight. Utvecklad av Telenor och är också en sans-serif font.

**Färgschema** -
Inte helt tydligt vilket färgschema som används. Ligger nog närmst analogt färgschema med blått som utgångsfärg. Skapar en känsla av pålitlighet.
[FIGURE src=image/mobile-operators/fargschema-telenor.PNG?w=300"]

**Laddningstid** -
Efter 11 omladdningar får jag medianvärdet 2.41 s och 1.7 mb laddas ner. Största bilden är 154 kb.

2.10, 2.16, 2.32, 2.35, 2.40, **2.41**, 2.55, 2.58, 2.65, 2.65, 2.90

Hos Google PageSpeed ger man Telenors hemsida ett bra betyg. Man även här tycker man det går att göra förbättringar på bilderna.

**Designprinciper** -
Påminner mycket om Telias design. Väldigt linjerbaserat  både horisontellt och vertikalt. Grid-baserat med god balans och har rörelser i huvudmenyn precis som konkurrenterna. Jag tycker de nedersta telefonen på bilden är oproportionellt små. I övrigt snygg hemsida.

[FIGURE src=image/mobile-operators/design-telenor.PNG?w=300"]

Sammanfattning
-----------------------
**Typografi** -
Serif fonterna lyser med sin frånvaro hos mobiloperatörerna. Man använder sans-serif fonter för att visa att man är moderna och hänger med i utvecklingen. Tele2 använder mest sina egna fonter så jag misstänker att de lägger mest tid på sin typografi. Omöjligt att säga om det gynnar dem eller inte. Telenor  använder en google font som används i bland annat hos Google+, Google Play, YouTube, Google Maps som användaren garanterat känner igen sedan tidigare.

**Färgschema** -
Det var inte helt enkelt att analysera färgscheman. Men samtliga har varit åt det analogt/monokromatiskt hållet vilket jag tror beror på att man vill skapa en känsla av seriositet. Man tar inte ut svängarna så mycket med färgpaletten. Färgvalen hos Telia och Telenor tilltalar mig mest.

**Laddningstid** -
Tele2 är laddningstestet stora vinnare. Jag kunde ladda deras startsida dubbelt så snabbt jämfört med Telias som kom på andra plats. Förhoppningsvis är Tele2 är trendsättare här som tvingar konkurrenterna att förbättras.  

**Designprinciper** -
Uppenbart väldigt trendigt att ha en meny som hoppar ner när man klickar på den. Det är något som alla tre operatörerna har. De jobbar väldigt mycket med linjer och grid. Jag trodde att det skulle finnas mera rörelser på sidorna. Men man prioriterar förmodligen att vara en seriös spelare utan "hopp och lek".

Övrigt
-----------------------

Fredrik Nelsson har gjort detta arbetet.
