---
title: "PsdColorPalette.IsCompactPalette"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdColorPalette-egenskap. Hämtar ett värde som indikerar om paletten är kompakt"
type: docs
weight: 70
url: /sv/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## PsdColorPalette.IsCompactPalette property

Hämtar ett värde som indikerar om paletten är kompakt.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` om paletten är kompakt; annars, `false`.

## Anmärkningar

Kompakt palett innebär att bilden endast kommer att innehålla de angivna palettposterna om möjligt, med andra ord blir bilden mer kompakt och upptar mindre utrymme; annars kommer det att finnas 2^BitsPerPixel poster och bilden kommer att reservera mer utrymme för alla möjliga palettposter. Att sätta detta värde till true och ändra palettposter kan medföra prestandapåverkan eftersom dataförflyttning kan ske, så använd det försiktigt.

### Se även

* class [PsdColorPalette](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


