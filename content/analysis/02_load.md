---
Title: Laddningstid
Descritption: Page about loading times
Template: analysis
---

Laddningstid
===============

I den här uppgiften ska jag välja tre webbsidor och tre sidor på webbplatsen och analysera de.

Urval
---------------
Jag valde hemsidorna: <a href="https://www.nike.com/se/en/">Nike</a>, <a href="https://www.youtube.com/">Youtube</a> och <a href="https://www.willys.se/">Willys</a>. Jag valde de här hemsidorna då de alla har en tydlig produkt som de visar upp. Då kan man lättare se hur mycket som bilder och embeds påverkar hemsidan hastighet.

Metod
---------------
För att utföra denna analys så använder jag mig av <a href="https://pagespeed.web.dev/">Pagespeed</a> för att se hemsidans prestanda. Jag använder mig även av firefox för att se nätverk och prestandan genom att inspektera hemsidan.

Nike
---------------
<img src="../image/nike.png" width="287px" height="248px">
För sidorna nike har jag valt de här sidorna: <a href="https://www.nike.com/se/en/w/new-3n82y">New & Featured</a>, <a href="https://www.nike.com/se/en/men">Men</a> och <a href="https://www.nike.com/se/en/women">Women</a> 

<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ69NHNUSDWjAbEvAOpIiSVotYVoPcUzFfWYcuuzFFb4ANgoViN80SW1uoXzE7lbxCZcCkDmET44jkp/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

Hemsidan skulle lätt kunna förbättras om bild storlekerna förmindras och storleken på själva hemsidan.

Youtube
---------------
<img src="../image/youtube.png" width="287px" height="248px">
För sidorna youtube har jag valt de här sidorna: <a href="https://www.youtube.com/">Hem</a>, <a href="https://www.youtube.com/feed/subscriptions">Prenumeranter</a> och <a href="https://www.youtube.com/feed/history">Historia</a> 

<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ69NHNUSDWjAbEvAOpIiSVotYVoPcUzFfWYcuuzFFb4ANgoViN80SW1uoXzE7lbxCZcCkDmET44jkp/pubhtml?gid=660326197&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

Hemsidan skulle lätt kunna förbättras med att förbättra JS laddningstid och ett för stort DOM som gör att det tar mer minne.

Willys
---------------
<img src="../image/willys.png" width="287px" height="248px">
För sidorna willys har jag valt de här sidorna: <a href="https://www.willys.se/">Hem</a>, <a href="https://www.willys.se/erbjudanden/butik">Erbjudanden</a> och <a href="https://www.willys.se/butik-sok">Hitta butik</a> 

<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ69NHNUSDWjAbEvAOpIiSVotYVoPcUzFfWYcuuzFFb4ANgoViN80SW1uoXzE7lbxCZcCkDmET44jkp/pubhtml?gid=1671619069&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

Hemsidan skulle lätt kunna förbättras är ett mindre DOM, förbättra JS laddningstid och mindre layoutförskjutning.

Analys
---------------
Med det här märker man att många av de här hemsidorna har onödig kod som inte används eller är redundant. Då jag inte nämnde det, så var det något som alltid kom upp. Det här kan vara som leder till "spaghetti kod" som ofta händer för sådana stora projekt som detta. Men något alla har problem är med ett för stort DOM. Då alla har en väldigt lång och stor hemsida med mycket info som behöver skrivas ut. Sedan är användning och beroende på JavaScript (JS) då de använder av mycket data.

Min rangordning skulle se ut så här:
1. Willys
2. Nike
3. Youtube

Då willys hade mycket mindre objekt så var det inte konstigt att förutse detta, samt är jag lite förvånad med hur lite objekt nike faktiskt använder sig av. Då youtube använder sig av mycket data och videor så är det inte en överraskning att de hamnade sist. Lite förvånad ibland hur långt tid det tog att ladda.

Sedan skulle jag säga att en hemsida inte ska ta längre än 5 sekunder att ladda. Den behöver inte vara helt klart med laddning på de här 5 sekunderna men man borde kunna se det mesta av innehållet och borde inte vara för slö. Hemsidor med en tydlig produkt bör ladda snabbt så man som användaren kan se produkten och jag tycker att för mestadels så upplever de här hemsidorna detta.

Övrigt
---------------
Kasper Holgersson, denna rapport har jag skrivit själv.
