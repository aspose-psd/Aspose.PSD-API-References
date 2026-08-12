---
title: "Enum TextRenderingHint"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.TextRenderingHint enum. Anger kvaliteten på textrendering"
type: docs
weight: 6200
url: /sv/net/aspose.psd/textrenderinghint/
---
{{< psd/tize >}}
## TextRenderingHint enumeration

Anger kvaliteten på textåtergivning.

```csharp
public enum TextRenderingHint
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| SystemDefault | `0` | Varje tecken ritas med sin glyf-bitmap, med systemets standardrenderingstips. Texten kommer att ritas med de teckensnabbningsinställningar som användaren har valt för systemet. |
| SingleBitPerPixelGridFit | `1` | Varje tecken ritas med sin glyf-bitmap. Hintning används för att förbättra teckenutseendet på stjälkar och kurvor. |
| SingleBitPerPixel | `2` | Varje tecken ritas med sin glyf-bitmap. Hintning används inte. |
| AntiAliasGridFit | `3` | Varje tecken ritas med sin antialiasade glyf-bitmap med hintning. Mycket bättre kvalitet på grund av antialiasing, men med högre prestandakostnad. |
| AntiAlias | `4` | Varje tecken ritas med sin antialiasade glyf-bitmap utan hintning. Bättre kvalitet på grund av antialiasing. Skillnader i stjälkbredd kan märkas eftersom hintning är avstängd. |
| ClearTypeGridFit | `5` | Varje tecken ritas med sin glyf ClearType-bitmap med hintning. Den högsta kvalitetsinställningen. Används för att utnyttja ClearType-funktioner i teckensnitt. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


