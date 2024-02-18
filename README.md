# Oblig1Data1700

HTML:
Oppgaven ba meg om å lage input bokser der man skal velge film, fylle ut antall billetter, og fulle navn, telefonnummer og epost
Hver felt har en feilmeldingboks som popper opp om informasjonen i feltene er feil. 
knappen "kjøp billett" registrerer informasjonen og setter det i en tabell, om all informasjonen er gyldig. den kaller til "registrer()" funksjonen.
knappen "Slett alle billetter" sletter informasjonen om billetten og kunden. den kaller til "slettBilletter()" funksjonen.


JAVASCRIPT: 
utInformasjon er en variabel som inneholder den gyldige informasjonen som blir lagd til om kunden
visPersonRegister() er en funksjon som oppretter en tabell med informasjon som blir lagret i utInformasjon-variablene og deretter sette det inn i tabellen
registrer() funksjonen tar imot data fra HTML-feltene og oppretter en personobjekt. 
Med denne infoen vil det bli lagd til personobjektet i utInformasjon-arrayen og oppdaterer deretter HTML-dokumentet.
validatePhoneNumber() og validateEmail() funksjonene gyldig-gjør telefonnummer 
og e-postadresser
validateInputs() funksjonen validerer alle inndataene fra feltet.
slettBilletter() funksjonen fjerner alle billetter fra utInformasjon-arrayen og oppdaterer HTML-dokumentet.



