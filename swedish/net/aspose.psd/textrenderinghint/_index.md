---
title: Enum TextRenderingHint
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.TextRenderingHint uppräkning. Anger kvaliteten på textåtergivningen.
type: docs
weight: 5700
url: /sv/net/aspose.psd/textrenderinghint/
---
## TextRenderingHint enumeration

Anger kvaliteten på textåtergivningen.

```csharp
public enum TextRenderingHint
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| SystemDefault | `0` | Varje tecken ritas med sin glyph-bitmapp, med systemets standardåtergivningstips. Texten kommer att ritas med de teckensnittsutjämningsinställningar som användaren har valt för systemet. |
| SingleBitPerPixelGridFit | `1` | Varje tecken ritas med sin glyph-bitmapp. Tips används för att förbättra karaktärens utseende på stjälkar och krökning. |
| SingleBitPerPixel | `2` | Varje tecken ritas med sin glyph-bitmapp. Tips används inte. |
| AntiAliasGridFit | `3` | Varje tecken ritas med hjälp av dess kantutjämnade glyph-bitmapp med antydan. Mycket bättre kvalitet på grund av kantutjämning, men till en högre prestandakostnad. |
| AntiAlias | `4` | Varje tecken ritas med hjälp av dess kantutjämnade glyph-bitmapp utan antydan. Bättre kvalitet tack vare kantutjämning. Skillnader i stambredd kan vara märkbara eftersom antydan är avstängd. |
| ClearTypeGridFit | `5` | Varje tecken ritas med sin glyf ClearType bitmapp med antydan. Den högsta kvalitetsinställningen. Används för att dra fördel av ClearType-teckensnittsfunktioner. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


