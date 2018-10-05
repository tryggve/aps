APS - Activity Planing System
===========

Alla goda ting är tre och i korta drag kan applikationens domän beskrivas genom tre saker.

![Enkel domänmodell](https://dl.dropbox.com/u/15846165/enkel_domanmodell.png)

En aktivitet har en eller flera uppgifter knutna till sig. Varje aktivitet likväl som varje uppgift har en ansvarig person. Personen kan vara en användare av systemet eller skriven i klartext.

Det finns ett [arbetsdokument][7] som kommer uppdateras under processen. Vi arbetar agilt =)


De tekniker som kommer användas är:

- [Backbone.js][1]
	Backbone är ett MVC-Ramverk som hjälper till med att ge applikationen en struktur och tydlig separation mellan modell och vy.
- [Underscore.js][2]
	Underscore är ett verktyg som har många väldigt användbara funktioner som du kan använda på Arrayer, Objekt och Collections som är en speciell typ utav samling specifik för Backbone.
- [Require.js][3]
	Require ger oss AMD i applikationen och innehåller även verktyg för att bygga appliaktionen.
- [Jasmine][4]
	Enhetstester kommer skrivas i Jasmine.
- [Twitter Bootstrap][5]
	Grafiska komponenter och en grundläggande layout.
- [jQuery][6]
	jQuery är bra att ha när man arbetar mot DOM:en och det kommer göras en del sådant.

Den primära användaren kommer förmodligen nyttja applikationen på en och samma surfplatta vid varje tillfälle så vi har möjlighet att utgå ifrån detta scenario vid planering av design och "cachening"...
Utöver detta kan vi titta på stöd för offline-arbete och hur local storage kan vara behjälpligt.
[Google Voice][8] är ytterligare en teknik som vi hoppas använda.

[1]: http://backbonejs.org/ "Backbone.js officiella webplats med dokumentation"
[2]: http://underscorejs.org/ "Underscores officiella webplats med dokumentation"
[3]: http://requirejs.org/ "Require.js officiella webplats med dokumentation"
[4]: https://jasmine.github.io/ "En introduktion till testramverket Jasmine"
[5]: http://twitter.github.com/bootstrap/ "Twitter Bootstrap är ett hjälpmedel för front end utveckling"
[6]: http://jquery.com "jQuery är ett bibliotek med genvägar till att manipulera DOM-strukturen"
[7]: https://docs.google.com/document/d/1JL0SXpobb4EvMf17dBEV2Q8Tw7jC8qz2w-tM4-rio0I/edit "Vision och lite annat smått och gott beträffande applikationen"
[8]: http://www.google.com/googlevoice/about.html "Om Google Voice"
