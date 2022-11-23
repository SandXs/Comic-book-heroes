##Read Me

#Week 1: 
-	Angular & NodeJS components downloaden/installeren 
-	Angular project aanmaken

#Week 2:
-	Starten aan basis van applicatie
-	Titel “Comic Book Heroes” gedefineerd in ‘app.component.ts’
-	Gedefineerde titel laten weergeven in ‘app.component.html’
-	Basis styling aan applicatie gegeven

#Week 3:
-	Component “heroes” aanmaken
-	Eigenschap “hero” aanmaken in ‘heroes.component.ts’
-	Geef eigenschap “hero” de waarde “Captain America” 
-	Bind data “hero” in ‘heroes.component.html’
-	Voeg het “<app-heroes>” component toe aan ‘app.component.html’
-	In ‘app’ folder maak ‘hero.ts’ aan

#Week 4: 
-	Vervang in ‘heroes.component.html’ data binding met de waarden “hero.name” en “hero.id” zodat meer gegevens weergeven #worden.
-	Zet “hero.name” – titel in ‘heroes.component.html’ naar uppercase om dit volledig in hoofdletters te weergeven.
-	Voeg input toe in ‘heroes.component.html’ om de naam van de heroes te wijzigen
-	Importeer “FormsModule” in ‘src/app/app.module.ts’

#Week 5:
-	In ‘app’ folder maak ‘mock-heroes.ts’ aan
-	Importeer “mock heroes” in ‘heroes.component.ts’
-	Wijzig ‘heroes.component.html’ zodat alle namen in een lijst komen te staan
-	Styling aan ‘heroes.component.html’ meegeven
-	Click event koppelen aan iedere hero om waarde aan te passen van geselecteerde hero

#Week 6:
-	Genereer module AppRoutingModule
-	Voeg “<router-outlet>” toe aan ‘app.component.html’ zodat de navigatie koppen zichtbaar worden
-	Voeg in ‘app.component.html’ boven “<router-outlet>” het element “<nav>” toe met daarin de routerLink naar Heroes
-	Genereer het component “dashboard”
-	In ‘dashboard.component.html’ zet je alle html zodat je een lijst krijgt van de top-heroes
-	Koppel ‘dashboard.component.ts’ aan heroes zodat je de heroes uit de lijst kan oplezen
-	Importeer dashboard in ‘dashboard.component.ts’ en voeg de path toe om deze werkend te maken
-	Maak dashboard de default path
-	Voeg in ‘app.component.html’ in het element “<nav>” de routeLink naar het dashboard toe

