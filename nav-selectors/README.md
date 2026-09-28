# nav-selectors

In deze oefening oefen je op de **descendant-selector** (spatie) en de **child-selector** (`>`). Bouw de opmaak uit `opgave.png` na.

* index.html
  * plaats in een `header` een `h1` met de titel "Kookclub De Gouden Pan" en daaronder een `nav`
  * in de `nav` maak je een ongeordende lijst met vier menu-items: Home, Recepten, Lidmaatschap en Contact. Elk menu-item is een link.
  * het menu-item "Recepten" krijgt een **submenu**: een tweede `ul` binnen datzelfde `li`-element, met de links Voorgerechten, Hoofdgerechten en Desserten
  * plaats na de `header` een `main` met een `h2` en een paragraaf. Zet in die paragraaf één link (bv. naar de huisregels).
  * sluit af met een `footer` met een paragraaf waarin ook een link staat
* vul de stylesheet in
  * alle tekst op de pagina krijgt een font-family van `Arial, Helvetica, sans-serif`
  * de `nav` krijgt `darkslategray` als achtergrondkleur en 10px padding
  * **alle** links in de `nav` worden wit en zijn niet onderlijnd, dus ook de links in het submenu. Gebruik hiervoor een descendant-selector.
  * bij alle lijsten in de `nav` verdwijnen de opsommingstekens
  * **enkel** de links van het hoofdmenu worden vetgedrukt en automatisch in hoofdletters geplaatst. De links van het submenu blijven gewone tekst. Gebruik hiervoor een child-selector, zodat de links van het submenu niet mee geselecteerd worden.
  * de links van het submenu krijgen een font-size van 14px en staan schuin

> Tip: het verschil tussen `nav a` en `nav > ul > li > a` is precies waar deze oefening over gaat. Bij een child-selector moet het element een **direct kind** zijn, bij een descendant-selector mogen er nog elementen tussen staan.

Controleer achteraf of je selectoren niet "lekken": de link in de `main` en de link in de `footer` moeten de standaardstijl van de browser houden (blauw en onderlijnd). Staan die ook wit of in hoofdletters, dan is je selector te breed.

## Verwacht resultaat

![nav-selectors](./opgave.png)
