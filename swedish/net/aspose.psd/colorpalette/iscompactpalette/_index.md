---
title: "ColorPalette.IsCompactPalette"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ColorPalette-egenskap. Hämtar eller anger ett värde som indikerar om kompakt palett används"
type: docs
weight: 60
url: /sv/net/aspose.psd/colorpalette/iscompactpalette/
---
{{< psd/tize >}}
## ColorPalette.IsCompactPalette property

Hämtar eller anger ett värde som indikerar om kompakt palett används.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` om kompakt palett används; annars `false`.

## Anmärkningar

Kompakt palett innebär att bilden endast kommer att innehålla de angivna palettposterna om möjligt, med andra ord blir bilden mer kompakt och upptar mindre utrymme; annars kommer det att finnas 2^BitsPerPixel poster och bilden kommer att reservera mer utrymme för alla möjliga palettposter. Att sätta detta värde till true och ändra palettposter kan medföra prestandapåverkan eftersom dataförflyttning kan ske, så använd det försiktigt.

### Se även

* class [ColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


