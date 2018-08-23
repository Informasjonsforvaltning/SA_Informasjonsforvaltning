# Bidra til SA_Informasjonsforvaltning arkitektur

## Instruksjoner
For å publisere dine endringer til github, må du være medlem av arkitektur-teamet. Deretter kan du følge denne oppskriften:

Først må du installere verktøy og plugin som beskrevet i [README.md](README.md)

### Jobbe med modellen i Archi
Inn til videre er det ikke støtte for branching i Archi, dermed må du gjøre følgende når du skal oppdatere modellen

#### Oppdatere HTML-rapporten
Når du har gjort vesentlige endringer i modellen, må du oppdatere HTML-rapporten. (Dette er en read-only html-versjon av modellen, som interessenter kan klikke rundt i.)
1. Velg File->Report->HTML...
2. Velg docs-mappa i prosjektet.
3. Trykk OK

Docs-mappa finner du lettest ved å finne Main->File i Properties-fanen for modellen. Erstatt ".git\temp.archimate" med "docs". Du vil få advarsel om at du overskriver eksisterende innhold. Det er ok, så trykk "Yes" i dialogen.
#### Commit
1.  Etter at du har gjort endringer, lagre disse på vanlig måte i Archi, feks CTLR+s
2.  Velg Collaboration->Commit Changes.
3.  Fyll ut feltene, bruk en fornuftig Commit message
4.  Trykk Ok

#### Publisere endringer til Github
1.  Etter at du har committet endringene, vil du publisere disse til Github
2.  Velg Collaboration->Publish Changes
Endringen blir da publisert på Github.

### Hvilke standarder og metoder har vi benyttet
*   Metodikk er basert på [TOGAF 9](http://pubs.opengroup.org/architecture/togaf9-doc/arch/)
*   Metamodellen er [Archimate 3](http://pubs.opengroup.org/architecture/archimate3-doc/)
