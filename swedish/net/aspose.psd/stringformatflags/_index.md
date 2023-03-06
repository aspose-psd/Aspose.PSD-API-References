---
title: Enum StringFormatFlags
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.StringFormatFlags uppräkning. Anger visnings och layoutinformation för textsträngar.
type: docs
weight: 5680
url: /sv/net/aspose.psd/stringformatflags/
---
## StringFormatFlags enumeration

Anger visnings- och layoutinformation för textsträngar.

```csharp
[Flags]
public enum StringFormatFlags
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Text visas från höger till vänster. |
| DirectionVertical | `2` | Texten är vertikalt justerad. |
| FitBlackBox | `4` | Delar av tecken tillåts hänga över strängens layoutrektangel. Som standard flyttas tecken om för att undvika överhäng. |
| DisplayFormatControl | `20` | Kontrolltecken som vänster-till-höger-markeringen visas i utgången med en representativ glyph. |
| NoFontFallback | `400` | Alternativa teckensnitt för tecken som inte stöds i det begärda teckensnittet är inaktiverat. Eventuella saknade tecken visas med teckensnitten som saknar glyf, vanligtvis en öppen ruta. |
| MeasureTrailingSpaces | `800` | Inkluderar det efterföljande utrymmet i slutet av varje rad. Som standard utesluter gränsrektangeln som returneras av metoden MeasureString utrymmet i slutet av varje rad. Ställ in denna flagga för att inkludera det utrymmet i måtten. |
| NoWrap | `1000` | Textbrytning mellan rader när formatering inom en rektangel är inaktiverad. Denna flagga antyds när en punkt passeras istället för en rektangel, eller när den angivna rektangeln har en linjelängd på noll. |
| LineLimit | `2000` | Endast hela linjer läggs ut i formateringsrektangeln. Som standard fortsätter layouten till slutet av texten, eller tills inga fler rader är synliga som ett resultat av klippning, beroende på vad som kommer först. Observera att standardinställningarna tillåter att den sista raden delvis skyms av en formateringsrektangel som inte är en hel multipel av linjehöjden. För att säkerställa att endast hela linjer syns, anger detta värde och var noga med att tillhandahålla en formateringsrektangel som är minst lika lång som höjden på en rad. |
| NoClip | `4000` | Överhängande delar av glyfer och olindad text som når utanför formateringsrektangeln tillåts att visas. Som standard klipps alla text- och glyfdelar som når utanför formateringsrektangeln. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


