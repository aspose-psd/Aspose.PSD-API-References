---
title: "StringFormatFlags Enumeratie"
type: docs
weight: 6300
url: /nl/python-net/aspose.psd/stringformatflags/
---

Specificeert de weergave‑ en layoulinformatie voor tekststrings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormatFlags

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Lidnaam** | **Beschrijving** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Tekst wordt van rechts naar links weergegeven. |
| DIRECTION_VERTICAL | Tekst is verticaal uitgelijnd. |
| DISPLAY_FORMAT_CONTROL | Besturingskarakters zoals het links-naar-rechts teken worden in de uitvoer weergegeven met een representatief glyph. |
| EXACT_ALIGNMENT | De exacte uitlijning, correcte opvulling GDI+ |
| FIT_BLACK_BOX | Delen van tekens mogen over de lay-outrechthoek van de tekenreeks uitsteken. Standaard worden tekens opnieuw gepositioneerd om elke uitstulping te voorkomen. |
| LINE_LIMIT | Alleen volledige regels worden geplaatst in de opmaakrechthoek. Standaard gaat de lay-out door tot het einde van de tekst, of tot er geen regels meer zichtbaar zijn als gevolg van afsnijden, afhankelijk van wat het eerst gebeurt.<br/>            Merk op dat de standaardinstellingen toestaan dat de laatste regel gedeeltelijk wordt verborgen door een opmaakrechthoek die geen geheel veelvoud is van de regelhoogte. Om ervoor te zorgen dat alleen volledige regels zichtbaar zijn,<br/>            specificeer deze waarde en zorg ervoor dat u een opmaakrechthoek opgeeft die minstens zo hoog is als de hoogte van één regel. |
| MEASURE_TRAILING_SPACES | Bevat de afsluitende spatie aan het einde van elke regel. Standaard sluit de begrenzingsrechthoek die wordt geretourneerd door de MeasureString-methode de spatie aan het einde van elke regel uit. Stel deze vlag in om die spatie mee te nemen in de meting. |
| NO_CLIP | Uitschietende delen van glyphs en niet-omgeslagen tekst die buiten de opmaakrechthoek komen, mogen worden weergegeven. Standaard worden alle tekst- en glyphdelen die buiten de opmaakrechthoek komen, afgeknipt. |
| NO_FONT_FALLBACK | Terugvallen op alternatieve lettertypen voor tekens die niet worden ondersteund door het aangevraagde lettertype is uitgeschakeld. Ontbrekende tekens worden weergegeven met het ontbrekende glyph van het lettertype, meestal een open vierkant. |
| NO_WRAP | Tekstomloop tussen regels bij opmaken binnen een rechthoek is uitgeschakeld. Deze vlag wordt geïmpliceerd wanneer een punt wordt doorgegeven in plaats van een rechthoek, of wanneer de opgegeven rechthoek een nul regel lengte heeft. |
