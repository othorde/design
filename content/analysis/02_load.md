---
Title: Load
Description: Part 1
Template: academic-report
---

Ikea, Webbdesignfabriken, Pinterest
=======================


I denna uppgift dokumenteras samt undersöks ovanstående företags laddningstid och prestanda.


Urval
=======================

Jag valde företagen Ikea, Webbdesignfabriken och Pinterest. 
En analys gjordes på Ikea och Webbdesignfabriken i föregående uppgift när färg skulle jämföras. Facebook gick ej att analysera genom Google Page speed. Därför valdes Pinterest istället.  Anledningen till att jag valde samma företag är att det kan vara intressant att jämföra inte bara de enskilda företagen i alla aspekter som ska göras i dessa uppgifter utan även hur de förhåller sig till varandra i alla kursmoment. 
<br><br>

<br><br>

Jag använde mig av devTools network flik för egna mätningar samt Google PageSpeed.
<br><br>

### Excell ark: 
<br><br>

https://docs.google.com/spreadsheets/d/1qoAstkpvK39T7gOZEwfYuFf621B8Az75cYsxk-fgQco/edit?usp=sharing

<br><br>




![IKEA](%base_url%/image/ikea.png){.pic}
<br><br>

![Webbdesignfabriken](%base_url%/image/webbdesign.png){.pic}
<br><br>

![Pinterest](%base_url%/image/pinterest.png){.pic}

<br><br>

https://www.ikea.com/se/sv/

<br><br>

https://webbdesignfabriken.se/

<br><br>

https://www.pinterest.se/

<br><br>

### Resultat 
<br><br>


### IKEA 
<br>
Ikea kan förbättra sin webbplats genom att läsa in resurser i förväg, använda modernare bildformat till bilder, ta bort onödig CSS och javascript samt minska serverns svarstid.
<br><br>

### Webbdesignfabriken 
<br>
Webbdesignfabriken kan förbättra prestanda genom bland annat minska serverns första svarstid. Ta bort oanvänd CSS och JavaScript som ej används samt minska påverkan från tredjepartskod. 

### Pinterest 
<br>
Pinterest bör minska samt ta bort oanvänd javascript, om möjligt. Bilderna bör vara i ett modernare format. Om möjligt bör de använda WebP där för de webbläsare som stödjer detta. Särskilt då det är en webbplats där en stor del är just bilder. De bör också skjuta upp inläsning av bilder som ej visas, dvs lazy loading. Det verkar dock som att de gör detta redan. Det verkar som att ca 1,5 sidor laddas in och när man sedan scrollar ner laddas nya bilder. 
<br><br>

### Sammanfattning resultat 
<br>

Resultaten är sämre än mina förväntningar. Jag förväntade mig att pinterest och Ikea skulle ha en högre rating på Google Pagespeed.  Det är mycket att ladda in på sidorna och de lär uppdatera sina webbsidor ganska frekvent med nya bilder och nya format. Att de inte använder rätt eller tillräckligt modernt format på sina bilder, ej läser in resurser i förväg, har oanvänd kod, var förvånande. Men det är stora webbplatser så jag antar att de borde ha koll på detta.
<br><br>
Kan det vara så att den oanvända koden kommer användas vid ett annat tillfälle? Att de har valt att ha kvar den för att inte behöva skriva ny när den ska användas igen? Använder Pinterest lazy loading men kanske inte avgränsat till en sida, dvs det användaren direkt ser. Om de vill att användaren ska stanna kvar på hemsidan vill de inte att sidan ska laddas långsammare än de skrollar. Är det därför webbplatsen verkar ladda in mer än en sida åt gången? Det verkar i alla fall finnas stora förbättringsmöjligheter för alla tre webbplatser. 
<br><br>
För att förbättra prestandan på hemsidan kan man komprimera filerna som är större än 150 kb i exempelvis verktyget Gzip. Man kan även minimera CSS, Javascript och HTML genom att ta bort alla onödiga tecken, oanvändbar kod och kommentarer. Detta kan göra att laddningshastigheten minskar avsevärt. Om man redirectar mycket på webbplatsen leder det också till sämre prestanda.
<br><br>
För att komprimera bilder behöver man använda andra verktyg för kompression. För att förbättra prestandan kan man se till att endast nödvändiga bilder laddas in och vid behov. Detta kallas lazy loading. Det är också viktigt att man använder rätt format på bilderna dvs, jpeg eller jpg för fotobilder, svg eller unicode för logos, ikoner och exempelvis PNG istället för GIF för bättre kompressions ratio. Man bör också se till att man inte laddar in för stora bilder än vad som behövs.
<br><br>
Om man använder sig av srcset bör man använda sig av sizes som ger tillräckligt med information till webbläsaren för att göra ett smart val av vilken bild som ska visas. Det gör att bilden kan visas snabbt. 
<br><br>
Övriga saker man kan göra för att förbättra laddningstiden är att nyttja cache, vilket många webbplatser redan gör men det innebär att man gör en kopia över senast använd data som lagras temporärt i minnet för att användas i framtiden. Serverns responstid är också viktig, optimal server responstid är under 200 ms.
<br><br>

### Webbplatser rangordnat. 

<br><br>
1.	Ikea
2.	Webbdesignfabriken
3.	Pintrest<br><br>

Den klara vinnaren är Ikea. Ikea fick bäst värden genom Google Pagespeed samt Google Pagespeed mobile. Ikea fick även bäst värden i devtools. På andra plats kommer webbdesignfabriken som ligger före i mätvärdena på Google Pagespeed men som också fick lite sämre värden i devtools.
<br>
<br>

### Egen uppskattad gräns för laddningstid.

<br>
Min önskade laddningstid är nog under två sekunder, det känns inte rimligt att vänta längre. Jag kan känna frustration efter 5-6 sekunder. Särskilt om man ska vidare på hemsidan och man måste göra detta flera gånger och inte kommer fram tillräckligt snabbt. Responstid från att jag trycker till att jag kommer in på pinterest och de första bilderna är laddade, känns som 4-5 sekunder och jag tycker det går lite långsamt. Ca 3 sekunder känns det som att Ikea tar. Webbdesignfabriken tar ca 10 sekunder från att jag tryckte nu till att jag kom till en färdig laddad sida. För lång tid. Då vill man bara göra en ny sökning och hitta det man letar efter på en annan sida. Den frustration jag känner är nog samma som för många och antagligen därför som det är bevisat att snabb laddningstid leder till bland annat högre försäljning. 
<br><br>
Det ska sägas att jag tyvärr sitter på ett mobilt bredband där täckningen inte är den bästa. Svårt att säga om mina mätvärden går att lita på.
<br><br>

### Författare
<br>
Denna rapport är skriven av Oliver Thordeman Andersson.
