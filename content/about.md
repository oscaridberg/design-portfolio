---
Title: About
Description: This is our about page.
---

About page
==========================
Jag har för detta kursmoment börjat style:a sidan med hjälp av enklare tekniker som Sass erbjuder. Färgerna som används på sidan är sparade i variabler för att man på så sätt ska kunna ändra på färgtemat på endast en plats istället för att behöva gå igenom varje element som använder färgerna. Det är visserligen möjligt att skapa variabler i de senaste versionerna av CSS men jag upplever att syntaxen för det är delvis lite krånglig, något som jag tycker att Sass har lyckats förbättra.

Vidare har jag delat upp header, main, och footer i separata moduler för att undvika att man får en oändligt lång .scss fil. Det är annars något som jag har haft problem med i tidigare kurser, att ens CSS fil blir alldeles för lång och det blir enkelt sagt väldigt komplicerat att hitta rätt element i filen. Istället för att försöka dela upp den i ett senare skede, tänkte jag att jag ser till att göra det rätt och enkelt för mig redan från början.

För att ytterligare styra upp mina filer har jag använt mig utav nesting, en funktion som jag verkligen har saknat när man skriver vanlig CSS. Jag tycker att filen får en bättre struktur och det gör det enklare att få en överblick av vilka regler som gäller för olika element.

Ett problem som jag dock har haft är att den mobila nav-baren slutar fungera korrekt när man börjar använda sig av Sass. Jag har försökt felsöka vad det är som gör det men har inte lyckats hitta en lösning på problemet. Istället har jag fått kommentera bort de delar som skapar hamburgemenyn.
