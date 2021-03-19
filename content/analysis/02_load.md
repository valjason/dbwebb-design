En analys av 3 webbplatser laddningstid och användbarhet
==============================================
I denna rapport undersöks utvalda webbplatsers laddningstid och användbarhet som signaleras ut för webbplatsens användare. Syftet med rapporten är att studera samt dokumentera 3 webbplatsers hastigheter och användarvänlighet samt diskutera och analysera hur sidan kan förbättras.

Urval
--------
Urvalet består av webbsidor från tre olika e-signerings företag. Detta för att jämföra hur de olika företagen har löst det första bemötandet mot sina kunder.

Den första webbplatsen som studeras är Scrives hemsida sedan undersöks hemsidor tillhörande Oneflow samt Contractbook.

Scrive: https://scrive.com

Oneflow: https://oneflow.com/

Contractbook: https://contractbook.com/

Metod
-----
För att utföra undersökningen så har jag använt mig att verktygen PageSpeed Insights, men även PageSpeed Insights, Devtools och Cache Checker.

Resultat
----------


![Scrive](./../content/analysis/scrive.jpg)
Scrives sida fick 77 i medelvärde för desktop efter tre mätningar, på mobil fick sidan 20 i medelvärde. Sidans totala storlek är 3,9 MB och tar i snitt 12 sekunder innan full interaktion är möjlig. Sidan gjorde ca 126 anrop per laddning och när väl extraherat så låg resurserna 7,2 MB.


![Oneflow](./../content/analysis/oneflow.jpg)
Oneflow fick 67 i medelvärde för desktop efter tre mätningar, för mobil fick sidan 19 i medelvärde. Sidans totala storlek är 23,1 MB och tar i snitt 18 sekunder innan full interaktion är möjlig. Sidan gjorde ca 177 anrop per laddning och när väl extraherat så låg resurserna 27,4 MB.

![Contractbook](./../content/analysis/contractbook.jpg)
Contractbook fick 51 i medelvärde för desktop efter tre mätningar, för mobil fick sidan 19 i medelvärde. Sidans totala storlek är 6.0 MB och tar i snitt 23 sekunder innan full interaktion är möjlig. Sidan gjorde ca 183 anrop per laddning och när väl extraherat så låg resurserna 12,5 MB.

Analys
---------
###Vanligaste förbättringsåtgärder i urvalet

Det finns en hel del förbättringsåtgärder för sidorna, de tre vanligaste som omnämns för urvalet av Scrive, Oneflow och Contractbook är dessa: 

Minska på antalet bilder i PNG format och använd JPG som alternativ, speciellt för porträttbilder. Gällande färger, flaggor eller stilistiska områden, använd mer vektorbilder för att öka prestandan. Komprimera även bilderna för att minska storleken vid överföring.

Alla företagen har bilder som användaren behöver skrolla ner till för att se, ytterligare en åtgärd för att förbättra prestandan gentemot bilder är att skjuta upp inläsningen av bilder som inte visas på skärmen.

Från vad jag har sett så använder samtliga sidor redan minifierad CSS, men det är alltid bra att arbeta med minifierad CSS och JS som tar bort kommentarer och komprimerar filerna som resulterar i snabbare inläsning.

Ytterligare förbättringsåtgärder är:

Skjuta fram inladdning av speciell CSS som sker längre ner på sidan för att kunna rendera det längst upp på sidan snabbare.

Det kan vara bra att anpassa sidan så att kod som är skrivet specifikt för äldre webbläsare endast läses om äldre webbläsare används.

Tredjepartskod kan vara bra att hålla till minimum då inläsning från andra servrar kan påverka renderings hastigheten.

Använd en lämplig cachelagring policy beroende på hur ofta front-end anpassas då det ökar inläsnings hastigheten.

Undvik att seriekoppla kritiska anrop som görs så att det inte hindrar inladdning av resterande om det skulle uppstå något problem.

Ta bort funktioner som inte nyttjas eller uppskattas av användare.

Komprimera med JSCompress, JavaScript Minifier, JavaScript Minifier, Minifiera, npm sass.

Undvik icke komposit animationer då det kan få animationer att se ojämna ut mobiler med sämre prestanda och resultera i förskjutning av layout.

Se till att all text förblir synlig medan webb teckensnitten läses in





###Vinnare


1. Scrive  

2. Oneflow  

3. Contractbook  


Scrive är vinnaren i det här testet fast alla sidor har många förbättringsmöjligheter, speciellt gällande inladdning av sidan på mobila plattformar.


Egen gräns för snabb och långsam sida

Var gränsen går gällande om en sida är snabb eller långsam kan variera då uppfattningen delvis är subjektiv. Min optimala gräns är under en sekund, därefter börjar det kännas onödigt långsamt och själv prioriterar jag handling före fina effekter, jag har sett att vi haft en övergång till användning av tyngre sidor, med fler effekter och rörliga bilder. 

De tre sidorna jag själv jämfört i den här analysen delar en hel del likheter där alla använder en viss modern, men även trendig stil på sidan. Den här trendiga stilen är dock inte speciellt optimal prestanda mässigt även om den kan vara optimerad.

I min åsikt så klarar inte någon av dessa sidorna min egna gräns, speciellt då vi har en stor andel trafik på mobila enheter.

Enligt Internetstiftelsen så använder majoriteten av svenskarna mellan 12 och 65 år internet.

Gällande internet i mobila enheter:
98-99% av svenskar mellan 12 och 45 år.
94% av svenskar mellan 46-55.
Motsvarande siffror för 56–65-åringarna är 90 procent och bland 66–75-åringarna 77 procent.
I åldersgruppen 76 år och äldre använder en minoritet, 38 procent, internet i mobilen.

I åldersgrupperna från 16–55 år är dator och mobil i stort sett lika förekommande för uppkoppling till internet. Siffrorna varierar mellan 94 och 99 procent. I åldrarna över 55 år blir dator det vanligaste sättet att ansluta till internet. Hos 56–65-åringarna använder 94 procent dator, jämfört med att 90 procent använder mobil. 

Då målgruppen för e-signering är internetanvändare så är det lönt att investera i att optimera webbsidorna även för mobila enheter.


Referenser
----------
https://docs.google.com/spreadsheets/d/1Hyd4RRLVlgP4KkdU9RHkUaiIFJKM5WBI6oFI4CoNrsA/edit?usp=sharing  

https://internetstiftelsen.se/kunskap/rapporter-och-guider/

Valério Wallin

