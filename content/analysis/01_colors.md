---
Title: Colors
template: technologies-single
description: Design Kmom04 - Utvärdera webbplatsers färgval och känsla
---

# Design Kmom04: Utvärdera webbplatsers färgval och känsla

Färger kan påverka hur en användare upplever en hemsida och kan väcka olika
typer av känslor. I den här rapporten går vi igenom tre olika hemsidor och
analyserar deras färg- och typografival för att se hur dom använder olika färger
för att förmedla ett budskap eller en känsla. <br><br>

## Urval

Vi kommer titta på olika hemsidor för skönhetskliniker. <br><br>

-   Estetica Ochoa -
    [https://www.esteticaochoa.com/](https://www.esteticaochoa.com/)
-   Centros Ideal -
    [https://www.centrosideal.com/](https://www.centrosideal.com/)
-   Centros Unico -
    [https://www.centrosunico.com/](https://www.centrosunico.com/) <br><br>

Alla är inom samma bransch men dom två sista är stora kedjor som fokuserar på
billiga priser och många klinker runtom i Spanien medan den första fokuserar på
en mer lyxig klinik. Vi kommer se ifall deras olika marknadsandelar och
inriktning påverkar deras färgval. Kommer dom billigare klinikerna försöka
utstråla en annan typ av känsla än den dyrare kliniken?  
<br>

## Metod

Jag gick igenom alla sidor och plockade ut huvudfärgerna och typografival.
Resultatet sammanställde jag i en HTML sida. För att få ut den exakta färgen
hemsidorna använde så användes Chrome tillägget ColorZilla men ibland plockades
färgerna ut direkt ur HTML koden via Chrome developer tools.

Typsnitten hemsidorna använder fick jag genom HTML koden och kunde ladda hem
fontfilen via Chrome Developer tools genom Network tools och filtrera ut enbart
fonts.

Analys utav färgerna gjordes genom
[https://www.colorhexa.com](https://www.colorhexa.com/),
[https://coolors.co/](https://coolors.co/) och Adobe Colors.

Jag använde alla typsnitten i förbestämda meningar för att kontrollera
tillgänglighet enligt industristandard.

Analys gjordes även av CSS koden som laddades ner via Network tools och jag
kunde plocka ut CSS regler som användes. Bilder av hemsidan gjordes genom att
köra ett av dom inbyggda Chrome scripten som kan nås via Windows genom att
trycka på Ctrl-Shift + I sen Ctrl-Shift + P och söka på screenshot <br><br>

## Resultat

### Estetica Ochoa

<a data-fancybox="single" href="../image/color/esteticaochoa_full.png">
<img style="max-width: 500px;" src="../image/color/esteticaochoa_full.png" />
</a> <br>

Estetica Ochoa använder sig utav en väldig simpel färgpalett vilket gör det
väldigt lätt för användaren att känna igen företagets branding. Sidan är väldigt
konsekvent i sitt utseende och färgval, det är bara vid fåtal ställen där dom
devierar från brandingen.

Huvudfärgen är <mark style="background-color: #E1A791">#E1A791</mark>, sekundära
färgen är <mark style="background-color: #EAC1B4"> #EAC1B4</mark> och dom
använder <mark style="background-color: #DBA38E">#DBA38E</mark> som highlight
färg. Tillsammans med huvudfärgerna använder sig även hemsidan utav
komplimenterande färgerna
<mark style="color: white; background-color: #4b4d51">#4b4d51</mark> för sina
CTA knappar, #2F5777 för CTA till personaler som jobbar på kliniken och
slutligen använder texten på hemsidan
<mark style="color: white; background-color: #4b4e52">#4b4e52</mark> <br><br>

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; background-color: #E1A791">
<td style="height: 50px; width: 50px; background-color: #EAC1B4">
<td style="height: 50px; width: 50px; background-color: #DBA38E">
<td style="height: 50px; width: 50px; background-color: #4b4d51">
<td style="height: 50px; width: 50px; background-color: rgba(47,87,119,0.8)">
<td style="height: 50px; width: 50px; background-color: #4b4e52">
</tr>
</table>
<br>

<a class="color-image" data-fancybox="single" href="../image/color/color-wheel_ochoa.png">
<img style="max-width: 500px;" src="../image/color/color-wheel_ochoa.png" />
</a> <br>
Typsnittet hemsidan använder sig utav är exklusivt bronkoh med färgen #4b4e52.
Typsnittet ger en vänlig och mjuk känsla till användaren. Med mjuka kurvor och
stora aperturer är typsnittet i överlag lättläst men inte helt anpassad efter
bästa tillgänglighets praxis.
<br><br>
<span style="font-size: 1.5em; font-family: bronkoh">
The quick brown fox jumps over the lazy dog<br>
<br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur consequat odio eu ligula vulputate, ac feugiat diam posuere. Curabitur consequat odio vel massa sodales malesuada.<br><br>
qp Il1
</span>
<br><br>
CSS styling kod för dom vanligaste elementen. 
Notera storleksvalen och dom olika letter spacing.

```css
h1 {
    margin-bottom: 16px;
    line-height: 1.3em;
    letter-spacing: 2px;
    font-size: 30px;
}

h2 {
    margin-bottom: 14px;
    line-height: 1.3em;
    font-size: 18px;
    letter-spacing: 1px;
}

h3 {
    text-align: center;
    margin-bottom: 10px;
    line-height: 1.3em;
    font-size: 18px;
    letter-spacing: 1px;
}
```

<br>

# **Centros Ideal**

<a data-fancybox="single" href="../image/color/ideal_full.jpg">
<img style="max-width: 500px;" src="../image/color/ideal_full.jpg" />
</a> <br>

Centros Ideal använder sig utav utav en lila färg som sin huvudfärg men det är
svårt att avgöra vad den exakta färgkoden är på grund utav ett väldigt
inkonsekvent användande av färgerna men min analys verkar peka på att
huvudfärgen är
<mark style="color: white; background-color: #90278E">#90278E</mark>. Det
inkonsekventa användandet av färger fortsätter runt om i hela sidan och att
avgöra dom sekundära färgerna är också svårt. Dom sekundära färgen verkar vara
<mark style="color: white; background-color: #D99ED6">#D99ED6</mark>,
tillsammans med mycket vitt och inslag av olika nyanser av
<mark style="color: white; background-color: #C6CBCE">#C6CBCE.</mark> <br><br>

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; background-color: #90278E">
<td style="height: 50px; width: 50px; background-color: #D99ED6">
<td style="height: 50px; width: 50px; background-color: #C6CBCE">
</tr>
</table>
<br><br>

<a class="color-image" data-fancybox="single" href="../image/color/color-wheel_ideal.png">
<img style="max-width: 500px;" src="../image/color/color-wheel_ideal.png" />
</a> <br>

Typsnittet sidan använder sig av är Raleway med olika font färger men oftast en
svart eller grå färg. Raleway är ett populärt Google Font från sans-serif
familjen. En lättläst och elegant font. Inkonsekvenserna fortsätter dock och det
finns tillfällen där jag har hittat andra typsnitt som tex Roboto. <br><br>

<span style="font-size: 1.5em; font-family: 'Raleway', sans-serif;">
The quick brown fox jumps over the lazy dog<br>
<br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur consequat odio eu ligula vulputate, ac feugiat diam posuere. Curabitur consequat odio vel massa sodales malesuada.<br><br>
qp Il1
</span>
<br><br>

CSS styling kod för dom vanligaste elementen. Väldigt svårt att få ut något
nyttigt utav det här eftersom stylingen är väldigt slumpässig och vi kan nästan
anta att den mesta styling är default value från deras template.

```css
h1 {
    text-transform: uppercase;
    font-size: 34px;
    font-weight: 555;
}

h2 {
    font-weight: 800;
    letter-spacing: 0;
    font-size: 29px;
    line-height: 1.2;
}

h3 {
    font-size: 1.077em;
    font-weight: 600;
    line-height: 1.5;
}
```

<br><br>

### Centro Unico

<a data-fancybox="single" href="../image/color/unico_full.png">
<img style="max-width: 500px;" src="../image/color/unico_full.png" />
</a> <br>

Använder sig sparsamt av sin huvudfärg
<mark style="color: white; background-color: #FF7F32">#FF7F32</mark> och den
sekundära färgen
<mark style="color: white; background-color: #F79B22">#F79B22</mark> men
tillsammans med svarta komplimenterande färger så sticker huvudfärgerna ut och
gör företagets färg väldigt lättigenkänt för användaren. CTA färgen
<mark style="color: white; background-color: #FFE0CC">#FFE0CC</mark> passar väl
in med dom andra färgerna och hemsidan är i stort sätt väldigt konsekvent i sitt
användande av färger förutom när det kommer till dom svarta färgerna där dom
använder sig av olika nyanser av svart på ett väldigt slumpmässigt sätt.
<br><br>

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; background-color: #FF7F32">
<td style="height: 50px; width: 50px; background-color: #f79b22">
<td style="height: 50px; width: 50px; background-color: #121212">
<td style="height: 50px; width: 50px; background-color: #FFE0CC">
</tr>
</table>
<br>

<a class="color-image" data-fancybox="single" href="../image/color/color-wheel_unico.png">
<img style="max-width: 500px;" src="../image/color/color-wheel_unico.png" />
</a> <br>

Typsnittet dom använder sig av är Gotham, ett typsnitt som används utav flera
stora företag och väldigt känt från bland annat Obamas 2008 presidentkampanj.
Sidan varierar dock flitigt mellan Gotham och Playfair Display – en Google font
som marknadsför sig som ett bra val i titlar men används till mestadels som
paragraftext av Centro Unico men det är värt att betona att sidan inte är
konsekvent i sitt användande och man hittar flera tillfällen är Playfair är font
till titlar och Gotham till text och vise versa. Navbaren använder sig utav
Montserrat, ytterligare ett väldigt vanligt Google font som används utav över 1
000 000 hemsidor. <br><br>

<span style="font-size: 1.5em; font-family: gotham">
The quick brown fox jumps over the lazy dog<br>
<br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur consequat odio eu ligula vulputate, ac feugiat diam posuere. Curabitur consequat odio vel massa sodales malesuada.<br><br>
qp Il1
</span>
<br><br>

## Analys

Hemsidorna är alla inom samma bransch men man kan se tydliga skillnader i
strategi och budskap som dom vill förmedla genom sina färgval. Ochoa var utan
tvekan hemsidan som var mest konsekvent i sitt användande av både färg och
typografi. Med tydliga och genomtänka färgval ger det användaren en tydlig
signal vad deras företagsidentitet är. Färgvalet ger en vänlig känsla och med en
mjuk sans-serif font förstärker dom känslan utav att vara vänliga men
professionella.

Färgvalet har dock inte ett idealt kontrastförhållande och huvudfärgen används
som bakgrundsfärg gentemot en vit text med ett kontrastförhållande av 2.07:1.
Bäst praxis är att bibehålla ett kontrastförhållande av 3:1 om texten är över
18pt eller 14pt bold och 4.5:1 för all annan text.

Färgvalen i Centros Ideal var till skillnad mot tidigare nämnda hemsida otroligt
inkonsekvent. Färgerna gick dock att känna igen och det är tydligt för
användaren att känna igen märket men från en designer och webbutvecklares
perspektiv så var hemsidan väldigt slarvigt gjort. Värt att nämna att Centros
Ideal är det största företaget över hundra kliniker runtom i Spanien och har
börjat expandera ut till andra länder så skulle man spontant kunna tro att ett
sånt företag hade lagt ner mer tid och energi på att ha en tydlig
företagsidentitet. Med allt det sagt så är sidan väldigt smart i sitt färgval
och genom att använda mycket vitt och grått utöver sina företagsfärger så ger
det användaren en känsla utav att dom är professionella och erfarna inom
medicin. Det här blir extra tydligt när man vill läsa mer om en specifik
behandling då man kan se hur många utav huvudfärgerna försvinner och blir till
accent färger istället och framsidan består till huvuddels av vita och gråa
toner för att förstärka det medicinska budskapet. Det är även värt att notera
att deras hero banner och många andra banners dom använder sig av tycks använda
andra färger än resten av hemsidan men färgerna komplimenterar vandra mycket
väl. Vi kan spekulera att Centros Ideal har anlitat en reklambyrå för att skapa
reklam för sina tjänster och produkter och dom har valt att använda egna
komplimenterande färger till hemsidans grundfärger.

Centros Ideal verkar vara baserat på ett wordpress template till att börja med
och vi kan finna många av dom vanliga wordpress komponeterna som stylas med
deras grundfärger men det funkar tyvärr inte alltid med kontrastförhållanden och
vi kan se exempel på förhållanden så lågt som 1.61:1.

Slutligen har vi Centro Unico som använder sig av en monokromatisk färgpalett
tillsammans med svarta highlights. Precis som Ochoa är färgvalen konsekventa.
Det här är sidan som är mest sparsam när det kommer till att använda sina färger
och förlitar sig på sina vita och gråa basfärger för att precis som Ideal ge
känslan av en vetenskaplig vinkling av deras tjänster. Tyvärr känns det som att
ibland saknar dom sin egen branding på grund av det väldigt begränsade
användandet av sina egna färger. Sidan hade utan tvekan varit mer intressant för
användaren om deras företagsfärger fick sättas i fokus tillsammans med dom vita
och svarta färgerna istället för att vara vad känns som en parantes i hemsidan
som det känns nu. Väldigt bra kontrastförhållande på sidan och allt är lätt läst
förutom deras CTA knappar längst upp på hemsidan där kontrastförhållandet ligger
på 2.07:1 som är långt under industrirekommendationer. Ett väldigt underligt val
med tanke på att man vill att sina CTA knappar ska sticka ut och vara tydliga
att se för användaren.

Sammanfattningsvis så finns det många likheter mellan alla hemsidor. Den
tydligaste är att alla förlitar sig på vita färger i många av sina sektioner för
att förmedla en vetenskaplig känsla. Det här påminner om hur företag tex
använder sig utav labbrockar till sin personal även om företaget inte har en
direkt koppling till medicin eller vetenskap.

Sidan som verkade ha den tydligaste strategin var Estetica Ochoa och sidan med
mest variation och avvikelser från sin egen brading var Centro Ideal. Det här
kan framstå som ironiskt eftersom Estetica Ochoa var den minsta kliniken i
urvalet med bara en klink och Centro Ideal var den största med över hundra
klinker.

Alla sidor har möjlighet att förbättra sina färgval på ett eller annat sätt men
huvudsakligen handlar det om att vara konsekvent i sitt användande av färger och
typsnitt och se över sin användartillgänglighet i form av bättre
kontrastförhållanden och eventuellt se över font val så några av dom inte höll
bästa praxis när det kommer till lättläslighet som tex qp och Il1 test.

<script src="https://cdn.jsdelivr.net/npm/@fancyapps/ui@4.0/dist/fancybox.umd.js"></script>
