---
title: Enum StringFormatFlags
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.StringFormatFlags opsomming. Specificeert de weergave en layoutinformatie voor tekenreeksen.
type: docs
weight: 5680
url: /nl/net/aspose.psd/stringformatflags/
---
## StringFormatFlags enumeration

Specificeert de weergave- en lay-outinformatie voor tekenreeksen.

```csharp
[Flags]
public enum StringFormatFlags
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Tekst wordt van rechts naar links weergegeven. |
| DirectionVertical | `2` | Tekst is verticaal uitgelijnd. |
| FitBlackBox | `4` | Delen van tekens mogen over de lay-outrechthoek van de tekenreeks hangen. Standaard worden tekens verplaatst om overhang te voorkomen. |
| DisplayFormatControl | `20` | Besturingstekens zoals de links-naar-rechts-markering worden in de uitvoer weergegeven met een representatieve glyph. |
| NoFontFallback | `400` | Terugval naar alternatieve lettertypen voor tekens die niet worden ondersteund in het aangevraagde lettertype is uitgeschakeld. Alle ontbrekende tekens worden weergegeven met ontbrekende glyph in de lettertypen, meestal een open vierkant. |
| MeasureTrailingSpaces | `800` | Bevat de volgspatie aan het einde van elke regel. De begrenzingsrechthoek die wordt geretourneerd door de methode MeasureString sluit standaard de spatie aan het einde van elke regel uit. Stel deze vlag in om die ruimte in de meting op te nemen. |
| NoWrap | `1000` | Tekstterugloop tussen regels bij opmaak binnen een rechthoek is uitgeschakeld. Deze vlag wordt geïmpliceerd wanneer een punt wordt gepasseerd in plaats van een rechthoek, of wanneer de opgegeven rechthoek een lijnlengte van nul heeft. |
| LineLimit | `2000` | In de opmaakrechthoek worden alleen hele regels opgemaakt. De lay-out gaat standaard door tot het einde van de tekst, of tot er geen regels meer zichtbaar zijn als gevolg van clippen, afhankelijk van wat zich het eerst voordoet. Merk op dat de standaardinstellingen toestaan dat de laatste regel gedeeltelijk wordt verborgen door een geheel veelvoud van de regelhoogte. Om ervoor te zorgen dat alleen hele lijnen zichtbaar zijn, specificeert deze waarde en zorgt u ervoor dat u een opmaakrechthoek opgeeft die minstens zo hoog is als de hoogte van één regel. |
| NoClip | `4000` | Overhangende delen van glyphs en onverpakte tekst die buiten de opmaakrechthoek valt, mogen worden weergegeven. Standaard worden alle tekst- en glyph-gedeelten die buiten de opmaakrechthoek reiken, afgekapt. |

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


