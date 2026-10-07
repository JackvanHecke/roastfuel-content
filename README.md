# Roastfuel — feitjes en fabels

De Roastfuel-app haalt `facts.json` op en toont de slides om de beurt.

- `kind`: `"feit"` of `"fabel"`. Bij een fabel staat de bewering in `myth` en het
  antwoord in `fact`.
- Elke tekst staat er in het Nederlands (`nl`) en in het Engels (`en`).
- Zet `updated` op de datum van je wijziging (JJJJ-MM-DD). De app negeert een lijst
  die ouder is dan de lijst die in de app zelf zit.
- Een `source` is verplicht. Een slide zonder bron of zonder een van beide talen
  wordt overgeslagen.

De app kijkt bij het openen en daarna om de paar uur of er een nieuwe versie is.
Zonder internet toont ze wat ze de vorige keer ophaalde, of anders de ingebouwde lijst.
