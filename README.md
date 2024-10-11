# stellastravel
Stellas travel

Stellas travel är en enkel portfolio med bilder från min Asia resa 2019. Webbplatsen har en responsiv layout, designad för att fungera smidigt på både datorer och mobila enheter.

Den inkluderar tre sidor: 
- En Bali sida 
- Em Filippinerna sida 
- En Enter sida, som tar en till Bali sidan. 

På varje sida kan man navigera sig till varje sida, även enter sidan. 


Funktioner och innehåll
- Hemsida: med en stor landskapsbild och en navigation till Portfolion.
- Navigationsmeny, som länkar till de olika sidorna (Bali, Filippinerna, och Enter Page).
- Bildgalleri med foton som kan visa olika resmål och upplevelser.
- Undersidor för varje resmål.
- Footer med upphovsrättsinformation.

Instruktioner för användning
1.Öppna webbplatsen: Ladda hemsidan genom att öppna `hemsida.html` i din webbläsare.
2. Navigera mellan sidor: Använd navigationsmenyn på vänster sida för att besöka undersidor för olika resmål.
3. Utforska bildgalleriet: Scrolla på huvudsidan för att se bilder från resan till Bali/Filippinerna.


Teknisk beskrivning
1. HTML-struktur
- Webbplatsen använder semantiska HTML-element som `<header>`, `<nav>`, `<main>` och `<footer>` för att skapa en strukturerad och tillgänglig layout.
- Alla sidor har en konsekvent navigationsmeny som underlättar navigering mellan sidorna.

2. CSS-styling och responsiv design
- Flexbox och CSS Grid används för layout och positionering av innehåll.
- Clamp används för att hantera dynamiska textstorlekar som anpassar sig efter skärmens bredd.
- Flera media queries anpassar layouten för olika skärmstorlekar:
  - På mobila enheter visas bilderna i en kolumn.
  - På surfplattor visas bilderna i två kolumner.
  - På större skärmar visas bilderna i tre kolumner.

3. Tillgänglighet
- Alt-attribut används för alla bilder för att förbättra tillgängligheten.
- Korrekt rubrikstruktur med `<h1>` och andra rubriker säkerställer bra läsbarhet och tillgänglighet.
- Färgkontraster mellan text och bakgrund har valts för att vara lättlästa.

4. Webbläsarverktyg
- Chrome DevTools användes för att debugga HTML och CSS samt testa responsiviteten på olika enheter.
- Wave och Lighthouse har använts för att säkerställa grundläggande tillgänglighet och optimera prestanda.

5. Versionshantering
- Git användes för att hantera projektets versioner, vilket gör det enkelt att spåra ändringar och samarbeta.

Installation och körning
1. Klona projektet till din lokala dator:
   ```bash
   git clone https://github.com/ditt-användarnamn/hemsida.git
