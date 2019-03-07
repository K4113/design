---
---
Laddningstid hos Sveriges mest sålda bilmärke
=======================

I denna rapport ska jag analysera laddningstiden för Sveriges tre mest sålda bilmärken.

Urval
-----------------------

Jag har valt att analysera de bilmärken som sålde mest första halvåret 2016 i Sverige.

Metod
-----------------------

Jag använde verktyget Google PageSpeed och de inbyggda utvecklarverktygen som finns i Google Chrome.


Resultat
-----------------------
[FIGURE src=image/car/data.PNG?w=300"]

[Länk till dokumentet med all data.](https://docs.google.com/spreadsheets/d/1QtBCqa31hXpAFCKK4COgtZSQwFufmBIHJwwWu8nkbcM/edit?usp=sharing)



######Volvo:
[FIGURE src=image/car/volvo.PNG?w=300"]
På volvos hemsida verkar man inte ha komprimerat bilderna speciellt mycket.
T ex så laddas bilderna nedan hem till användaren med väldigt stora storlekar.
Det måste vara möjligt att få ner storleken här.

- hero_ocean_accessories_4096x2304.jpg (2.0mb)
- hero_v60_sunset_cbv_4096x2304.jpg (1.4mb)
- cross-country/v433_galleryimage_2.jpg (1mb)

######Volkswagen:
[FIGURE src=image/car/volkswagen.PNG?w=300"]
Volkswagens bilder är mindre än volvos. PageSpeed Insight rekomenderar att byta till modernare bildformat.

######BMW:
[FIGURE src=image/car/bmw.PNG?w=300"]
För BMW rekomenderas att ta bort resurser som blockerar renderingen av sidan. Samtliga bilder är under 122 kb!

Analys
-----------------------

Samtliga hemsidor upplevs snabbare från ett användarperspektiv än vad mitt resultat visar.
Det beror på att toppen av sidan renderas först och man tror att sidan är färdigladdad när botten fortfarande laddas.
Min hypotes är att biltillverkarna kan leva med de långsamma hemsidorna tack vara detta.

Den vanligaste förbättringspotentialen är att arbeta med bildernas format och storlekar.

Jag utnämner BMW till vinnare i detta test trotts att Volvos hemsida laddas snabbare. BMW har minst dåligt resultat på pagespeed insights och har arbetet mest med bilderna. Användaren tvingas att ladda ner drygt sex gånger mindre data än hos konkurrenterna. Volvo får silvermedalj och Volkswagen får nöja sig med brons.

Jag tycker en hemsida max får ta ett par sekunder att ladda. Annars tror jag det finns en stor risk att användaren tröttnar.
Hemsidorna i denna rapport får godkänt tack vare att användaren upplever att sidan är klar snabbare än vad den är.  

Referenser
-----------------------

https://teknikensvarld.se/sveriges-mest-salda-bilmarken-har-ar-listan-316040/

Övrigt
-----------------------

Fredrik Nelsson har gjort detta arbetet.
