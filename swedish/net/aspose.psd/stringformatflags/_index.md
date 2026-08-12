---
title: "Enum StringFormatFlags"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.StringFormatFlags-enum. Anger visnings- och layoutinformation för textsträngar"
type: docs
weight: 6180
url: /sv/net/aspose.psd/stringformatflags/
---
{{< psd/tize >}}
## StringFormatFlags enumeration

Anger visnings- och layoutinformation för textsträngar.

```csharp
[Flags]
public enum StringFormatFlags
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Text visas från höger till vänster. |
| DirectionVertical | `2` | Text är vertikalt justerad. |
| FitBlackBox | `4` | Delar av tecken får hänga utanför strängens layoutrektangel. Som standard omplaceras tecken för att undvika överhäng. |
| DisplayFormatControl | `20` | Kontrolltecken såsom vänster‑till‑höger‑markering visas i resultatet med en representativ glyf. |
| NoFontFallback | `400` | Reserv till alternativa teckensnitt för tecken som inte stöds i det begärda teckensnittet är inaktiverad. Eventuella saknade tecken visas med teckensnittets saknade glyf, vanligtvis en öppen ruta. |
| MeasureTrailingSpaces | `800` | Inkluderar efterföljande mellanslag i slutet av varje rad. Som standard exkluderar rektangeln som returneras av MeasureString‑metoden mellanslaget i slutet av varje rad. Aktivera detta flagg för att inkludera mellanslaget i mätningen. |
| NoWrap | `1000` | Textbrytning mellan rader vid formatering inom en rektangel är inaktiverad. Detta flagg antas när en punkt skickas istället för en rektangel, eller när den specificerade rektangeln har en linjelängd på noll. |
| LineLimit | `2000` | Endast hela rader läggs ut i formateringsrektangeln. Som standard fortsätter layouten tills slutet av texten, eller tills inga fler rader är synliga på grund av beskärning, beroende på vad som inträffar först. Observera att standardinställningarna tillåter den sista raden att delvis döljas av en formateringsrektangel som inte är ett helt multipel av radens höjd. För att säkerställa att endast hela rader visas, ange detta värde och var noga med att tillhandahålla en formateringsrektangel som är minst lika hög som höjden på en rad. |
| NoClip | `4000` | Överhängande delar av glyfer och oinsvept text som når utanför formateringsrektangeln får visas. Som standard klipps all text och glyfdelar som når utanför formateringsrektangeln. |
| ExactAlignment | `8000` | Den exakta justeringen, korrekt utfyllnad GDI+ |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


