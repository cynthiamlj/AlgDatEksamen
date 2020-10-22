# Mappeeksamen i Algoritmer og Datastrukturer Høst 2020

# Krav til innlevering

Se oblig-tekst for alle krav, og husk spesielt på følgende:

* Git er brukt til å dokumentere arbeid (minst 2 commits per oppgave, beskrivende commit-meldinger)	
* git bundle er levert inn
* Hovedklassen ligger i denne path'en i git: src/no/oslomet/cs/algdat/Eksamen/EksamenSBinTre.java
* Ingen debug-utskrifter
* Alle testene i test-programmet kjører og gir null feil (også spesialtilfeller)
* Readme-filen her er fyllt ut som beskrevet


# Beskrivelse av oppgaveløsning (4-8 linjer/setninger per oppgave)

Vi har brukt git til å dokumentere arbeidet vårt. Jeg har 16 commits totalt, og hver logg-melding beskriver det jeg har gjort av endringer.

* Oppgave 1: Løste ved å implementere ...
* Oppgave 2: Løste ved å bruke en while loop lik som den i inneholder, bare at i "else" statementet så plusser den på <br/>
1 på count variabelen og går videre til høyre for å finne flere frem til den ikke lenger finner fler. <br/> 
Går til høyre fordi den leter etter duplicates og tall som er større eller lik verdi ligger alltid til høyre
* Oppgave 3: <br/>førstePostorden ble løst ved bruk av rekursjon, denne sender med enten p.høyre eller p.venstre ettersom
hvilke av de som er NULL eller ikke. <br/>nestePostorden ble løst ved hjelp av if-setninger som oppfyller sjekklisten under punkt 5.1.7 i kompendiet.
* Oppgave 6: I fjern metoden la jeg merke til at ved tilfelle 2 (p har eksakt et barn) så pekte barnet til den fjernede noden
sin foreldre peker til den fjernede noden. Her la jeg til if(b!=null) b.forelder = q; Jeg måtte også legge til if (b != null) b.foreler = null, inne i if (p == rot) Dette fikset problemet med foreldre pekerne.