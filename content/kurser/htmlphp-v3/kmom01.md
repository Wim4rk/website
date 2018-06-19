---
author:
    - mos
revision:
    "2018-06-08": (prel, mos) Nytt dokument inför uppdatering av kursen.
    "2017-09-01": (G, mos) Video till installation av dbwebb-cli.
    "2017-06-15": (F, mos) Ny struktur labbmiljö.
    "2016-08-31": (E, mos) Lade till rätt videoserie från youtube.
    "2016-02-22": (D, mos) Bort med not om kursutveckling och länk till version 1.
    "2015-08-27": (C, mos) Lade till länkar till introduktion om HTML och CSS.
    "2015-08-17": (B, mos) Länk till forumet om statisk kodvalidering.
    "2015-08-06": (A, mos) Första utgåvan för htmlphp version 2 av kursen.
...
Kmom01: Bygg en webbplats
==================================

[WARNING]

**Kursutveckling pågår till kurs htmlphp v3**

Kursstart hösten 2018.

[/WARNING]

Kursmomentet visar hur du kommer igång med labbmiljön, dels via en installation på din egen dator och dels genom att publicera resultatet på driftsservern. Du kommer att utveckla din kod lokalt och därefter kopiera över resultatet till en driftsserver.

Du skall gå igenom ett par exempel på kodning i HTML, CSS och PHP och använda lärdomarna för att bygga en me-sida. Me-sidan är en enkel webbplats som innehåller en presentation av dig själv tillsammans med redovisningstexterna för kursmomenten.

<!--more-->

Vi bygger webbplatsen tillsammans, steg för steg. Vi försöker bygga en struktur som går att återanvända för att bygga fler och större webbplatser.

[FIGURE src=/image/snapvt15/me-done.png?w=w2 caption="En me-sida som den kan se ut när den är klar."]

När vi är klara med dagens övning så har du förhoppningsvis fått lite blodad tand på det som kursen handlar om. Tanken med övningen är att du skall bekanta dig med de grundtekniker (HTML, CSS, PHP) som kursen omfattar och få möjlighet att se hur de samverkar. I kommande kursmoment tittar vi mer ingående på respektive teknik.

<small><i>(Detta är instruktionen för kursmomentet och omfattar det som skall göras inom ramen för kursmomentet. Momentet omfattar cirka **20 studietimmar** inklusive läsning, arbete med övningar och uppgifter, felsökning, problemlösning, redovisning och eftertanke. Läs igenom hela kursmomentet innan du börjar jobba. Om möjligt -- planera och prioritera var du vill lägga tiden.)</i></small>



Labbmiljön  {#labbmiljo}
---------------------------------

*(ca: 2-4 studietimmar)*

Det första du behöver göra är att installera en labbmiljö för kursen. Om detta är din första dbwebb-kurs så kan det innebära en hel del jobb och en del nya tekniker. Se till att du har gott om tid när du gör detta.

Om du vill ha en introduktion till det som händer i steg 2-4 så kikar du på videon "[Mikael installerar dbwebb-cli som en del av labbmiljön](https://www.youtube.com/watch?v=vlZRW2OZamE)".

1. Du kan börja med att [installera labbmiljön](./../labbmiljo) som behövs för kursen. 

1. Fortsätt med sektionen för att [installera kommandot `dbwebb`](dbwebb-cli/kom-igang-och-installera). Kommandot används under hela kursen för att jobba med kursmaterialet.

1. När du har installerat kommandot så fortsätter du med sektionen för att [konfigurera kommandot `dbwebb`](dbwebb-cli/konfiguration).

1. Du kan nu [ladda ned (klona) ditt lokala kursrepo `htmlphp`](dbwebb-cli/clone) som innehåller kursmaterial för kursen. Här kommer du att skriva all kod till övningar och uppgifter.



Läsanvisningar  {#lasanvisningar}
---------------------------------

*(ca: 4-8 studietimmar)*


### HTML {#html}

Läs följande för att bekanta dig med tekniken.

1. Läs igenom följande sektion i guiden "[Kom igång med HTML](guide/kom-igang-med-html)".
    * 

1. HTML - [Gör din första sida med HTML5](coachen/gor-din-forsta-sida-med-html5)

1. [HTML och CSS-boken](kunskap/boken-html-och-css-boken)
    * Inledning
    * Kapitel 1 Snabbstart
    * Kapitel 2 Grunderna i HTML

(referens till html element)



### CSS {#css}

Läs följande för att bekanta dig med tekniken.

1. Läs igenom följande sektion i guiden "[Kom igång med CSS](guide/kom-igang-med-css)".
    * 

1. CSS - [Styla din sida med CSS och en extern stylesheet](coachen/styla-din-sida-med-css-och-en-extern-stylesheet)

(referens till css selectorer)



### PHP {#php}

Läs följande för att bekanta dig med tekniken.

1. Läs igenom följande sektion i guiden "[Kom igång med programmering i PHP](guide/kom-igang-med-programmering-i-php)".
    * [Introduktion](guide/kom-igang-med-programmering-i-php/introduktion)
    * [Grunder och struktur](guide/kom-igang-med-programmering-i-php/grunder-och-struktur) 

1. I kursboken [Webbutveckling med PHP och MySQL](kunskap/boken-webbutveckling-med-php-och-mysql) är följande kapitel relevanta att läsa igenom.
    * Kapitel 1 Introduktion
    * Kapitel 2 Variabler (ej vektor, objekt, 2.4 Miljövariabler)
    * Kapitel 4 Operatorer

<!--
[INFO]
**Tips**

Bekanta dig med PHP-manualen. Det kan bli en av dina bästa vänner. Allt du behöver veta om PHP finns att läsa i manualen. Det gäller bara att bli kompis med manualen.

[Läs lite kort om språket PHP](http://php.net/manual/en/intro-whatis.php) och slå upp [funktionen include()](http://php.net/manual/en/function.include.php) och läs lite om den. Det kan se lite kryptiskt ut vid första anblicken, men lär dig läsa manualen så är mycket vunnet.
[/INFO]
-->



<!--
1. Del 1-5, 7 av artikeln [Kom i gång med PHP på 20 steg](kunskap/kom-i-gang-med-php-pa-20-steg)

1. Videoserien [Lär dig PHP](https://www.youtube.com/playlist?list=PLKtP9l5q3ce_U0j3HFq9pTVWvr-YQvy0B) är tätt kopplat till kursmaterialet. Kika på de videor som börjar med 0 och 1.
-->



Övningar & Uppgifter  {#ovningar_uppgifter}
-------------------------------------------

*(ca: 6-10 studietimmar)*



### Övningar {#ovningar}

Genomför följande övning för att träna dig och förbereda inför uppgifterna.

1. Jobba igenom övningen "[Gör en me-sida med HTML, CSS och PHP](kunskap/skapa-en-webbsida-med-html-css-och-php)". Övningen innehåller grunderna i HTML, CSS och PHP och visar hur du bygger upp en enkel webbplats. Filerna du jobbar med kan du spara i `me/kmom01/me`.



### Uppgifter {#uppgifter}

Dessa uppgifter skall utföras och redovisas.

1. Gör uppgiften "[PHP lab 1: uttryck, datatyper och variabler](uppgift/php-lab1-uttryck-datatyper-och-variabler)". Spara alla filerna i katalogen `me/kmom01/lab1`.

1. Gör uppgiften "[Skapa en me-sida i kursen htmlphp](uppgift/skapa-en-me-sida-i-kursen-htmlphp)". Detta blir grunden till din me-sida i kursen. Spara alla filerna i katalogen `me/kmom01/me1`.



<!--
### Extra {#extra}

Det finns inga extra uppgifter.

1. Ibland behöver du flytta filer mellan din lokala dator och din webbserver (dock inte i denna kursen eftersom vi gör på ett annat sätt). Då kan ett verktyg som Filezilla, en FTP/SFTP-klient vara till hjälp. Kör igenom artikeln "[Flytta filer till driftsmiljön med sftp och Filezilla](kunskap/flytta-filer-till-driftsmiljon-med-sftp-och-filezilla)" för att lära dig hur det fungerar.

1. Läs kort om [statisk kodvalidering av PHP-kod](t/4441).
-->



Resultat & Redovisning  {#resultat_redovisning}
-----------------------------------------------

*(ca: 1-2 studietimmar)*

Läs [instruktionen om hur du skall redovisa](./../redovisa).

Se till att följande frågor besvaras i redovisningstexten.

* Vilken utvecklingsmiljö använder du?
* Är du bekant med HTML, CSS och PHP sedan tidigare?
* Gick det smärtfritt att installera labbmiljön eller fick du bekymmer?
* Är du bekant med terminalen och Unix-kommandon sedan tidigare?
* Gick det bra att komma i gång med kursmomentet, var det lagom, för litet, för stort?
* Gjorde du någon av extrauppgifterna? Berätta om det arbetet isåfall.