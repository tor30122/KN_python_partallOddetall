# Er det partall eller oddetall?

**Mål:**  
Lag et lite Python‑program som spør brukeren om et heltall og deretter skriver ut om tallet er partall eller oddetall.

**Eksempel på kjøring**

``` terminal
Skriv inn et tall: 42
Tallet er partall.
```

``` terminal
Skriv inn et tall: 17
Tallet er oddetall.
```

*(Programmet fortsetter å be om nye tall hvis du oppgir ugyldig input.)*

## Krav

- [ ] Koden er skrevet i Python og bruker ingen eksterne biblioteker  
- [ ] Programmet ber brukeren skrive inn et positivt heltall (kan også være negativt, men skal fortsatt tolkes som heltall)  
- [ ] Programmet avgjør om tallet er partall eller oddetall ved hjelp av modulo‑operatoren `%`  
- [ ] Resultatet skrives ut i formatet “Tallet er **partall**.” eller “Tallet er **oddetall**.”  
- [ ] Programmet sjekker at input kan tolkes som et heltall og, hvis ikke, ber om nytt input.  

## Tips

- Bruk `int()` for å konvertere strengen til et heltall og håndter `ValueError` hvis brukeren skriver noe annet enn tall.  
- Modulo‑operatoren `%` returnerer resten av divisjon; hvis resten er 0 (`tall % 2 == 0`) er tallet partall.  
- Ingen eksterne biblioteker trengs – kun grunnleggende Python‑funksjoner og -kontrollstrukturer.  
