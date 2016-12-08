---
titleBreadcrumb: Designprinciper
...

Designprinciper
=================
Här beskriver jag de nya teman jag skapat, som du hittar i [temaväljaren](theme-selector).
De olika designprinciperna har jag tagit från [Design Elements & Principles](https://designschool.canva.com/design-elements-principles).

##Depth
Jag har försökt skapa djup på sidan genom text-shadow och box-shadow.
Logotexten, h1, h2 och bilder har alla en skugga som får dem att kännas framflyttade från
bakgrunden de är fastklistrade på. Jag har även använt skugga på bilder
och "selected"-element. Alltså är den sida i navbaren och sidebaren man för stunden
är inne på också lite framflyttad genom skuggning.

##Repetition
Jag har använt en bakgrundsbild med ett grönt mönster på flera element som gör att
det är uppenbart vilken sida man är inne på. Om mönstrena är kännetecknande för till
exempel ett företag eller liknande så kan det vara ett sätt pränta in dessa mönster i huvudet på folk
vilket gör att de kommer minnas det. Repeterande av mönster kan skapa enhet även om mycket
annat av webbplatsens style ändras från sida till sida.

##Direction
Element som sidebar och main dyker upp på skärmen efter hand genom en övergång från 0 opacity till
1. Ett liknande sätt kan göra det lättare för användaren att veta vad den ska lägga ögonen på innan
all information har dykit upp på skärmen. Jag tycker egentligen inte den här tekniken är så jättelämplig
för just den här webbplatsen, men jag tror definitivt man hade kunnat få det att fungera bra på en lämplig sida.
Jag använder mig av animation-propertyn i CSS och @keyframes för den som undrar hur det fungerar.
