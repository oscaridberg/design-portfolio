---
Title: Laddningstid
Description: Rapporten fokuserar på att analysera laddningstid och användarbarhet på tre utvalda hemsidor.
Template: reports
---
I den här rapporten kommer vi att analysera tre webbplatser och jämföra hur snabba sidorna är och därmed också hur användbara dessa är.

Urval
-----------------------
I den här rapporten har vi valt att analysera tre stora nyhetssidor. De sidor vi har valt är Aftonbladet, SVT och CNN, vi valde dem eftersom de alla är sidor med mycket innehåll och många besökare. På varje hemsida har vi valt ut att kolla startsidan, sportsidan och kultursidan.
www.aftonbladet.se
www.svt.se
www.cnn.com

Metod
-----------------------
Vi har använt oss av Firefox Devtools, PageSpeed och Google Lighthouse för att samla in mätvärden för de tre hemsidorna. Vi har i tabellen med det genomsnittliga värdet av laddningstid, storlek och antal resurser både med och utan adblock från Devtools samt betyg från Google Lighthouse. Vi har inte med något från PageSpeed då vi inte fick fram värden till alla sidor och därför inte fick resultat som vi kunde analysera. Vi har även använt Google Lighthouse för att se vad sidorna skulle kunna förbättra för att bli snabbare.
https://pagespeed.web.dev/

###Aftonbladet

<fig class="img-container"><img src="../assets/img/aftonbladet.jpg" width="500"></fig>

* https://www.aftonbladet.se/
* https://www.aftonbladet.se/sportbladet
* https://www.aftonbladet.se/kultur


###SVT

<fig class="img-container"><img src="../assets/img/svt.jpg" width="500"></fig>

* https://www.svt.se
* https://www.svt.se/sport/
* https://www.svt.se/kultur/

###CNN

<fig class="img-container"><img src="../assets/img/cnn.jpg" width="500"></fig>


* https://www.cnn.com
* https://edition.cnn.com/sport
* https://edition.cnn.com/entertainment

Resultat
-----------------------

<div class="excel-wrapper">
    <iframe class="excel" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSJv6LVpTcky13QiQ1xpSzFhe6pODYxv8QuM12Vngtz3EHMSbXDRFFJmYyCpvAvTjCP5v2_jHP7twyx/pubhtml?widget=true&amp;headers=false"></iframe>
</div>







Aftonbladet skulle kunna förbättra sin webbplats genom att skicka rätt storlek på sina bilder, alltså inte onödigt stora bilder samt att minska JavaScript i reklam. Överlag skulle reklamen kunna ta mindre plats då det är den som tar mest plats och gör sidan långsam.
SVT får generellt ett bra betyg från Google Lighthouse men om den ska förbättras så skulle det kunna vara genom att kolla över JavaScript. Bilderna som skickas är små men med bra kvalitet så det gör de bra.

CNN har stor förbättringspotential och skulle kunna göras snabbare om de ser över fontladdningen, vilken font de använder. De kan också skicka rätt storlek på bilderna, ta bort oanvänd JavaScript, se över DOM-trädets storlek samt använda document.write() i lägre utsträckning då det kan ställa till problem för användare med dålig uppkoppling.


Analys
-----------------------
Vi såg ganska snabbt in i undersökningen att reklamen på Aftonbladet och CNN spelar stor roll för både snabbhet och storlek på sidorna. Därefter kan vi i resultatet se att SVT, som inte har någon reklam på sin webbplats,  har en betydligt mycket snabbare sida än de andra. Vi kan se att startsidan på varje webbsida är snabbare än undersidorna sport och kultur och det är genomgående för alla tre webbsidor.
Den vanligaste förbättringsåtgärden som vi kan se på alla tre webbplatser verkar vara att kolla över och rensa onödig JavaScript. Utöver det är en annan förbättringsåtgärd att se över storleken på bilderna, något som både Aftonbladet och CNN skulle kunna justera för att göra sidorna snabbare.
När vi använde Pagespeed för att analysera sidorna tyckte vi att resultaten var orimliga, till exempel fick vissa sidor 30-40 sekunder innan de var interactive vilket inte återspeglade vår upplevelse när vi själva besökte sidorna. För vissa av sidorna fick vi inget resultat överhuvudtaget vilket gjorde att vi valde att överge Pagespeed till förmån för Google Lighthouse som verktyg för våra analyser.

Rangordning baserat på laddningstid
-----------------------
Vi diskuterar och kommer fram till att en sida som laddar på 1 sekund och mindre är en snabb och bra webbsida. När en webbsida laddar långsammare än så, upp mot 2, 3 sekunder och även långsammare så klassar vi det som en långsam sida. Vi tror att det kan göra att besökaren tappar intresset och inte uppskattar besöket.
Baserat på de uppmätta värdena anser vi att SVT är den klara vinnaren med 0.9 sekunders laddningstid för startsidan och under 1.5 sekunders laddningstid för sport- och kultursidorna. SVT har också på ett bra sätt optimerat sina bilder vilket bidrar till det fina resultatet.
På andra plats i vår bedömning kommer Aftonbladet vars förstasida laddas in på i snitt 1.51 sekunder, inget dåligt resultat men den längre laddningstiden är kännbar.
Sist kommer CNN. Här tar det hela 2.25 sekunder för förstasidan att laddas in vilket är en markant skillnad mot SVT och gör att hela sidan känns långsam.

Referenser
-----------------------
* https://pagespeed.web.dev/
* https://developer.mozilla.org/en-US/docs/Tools?retiredLocale=sv-SE
* https://developers.google.com/web/tools/lighthouse

Övrigt
-----------------------
Agnes Rodhe,
Mattias Eriksson,
Oscar Idberg
