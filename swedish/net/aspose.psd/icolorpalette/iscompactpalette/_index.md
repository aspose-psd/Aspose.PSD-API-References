---
title: "IColorPalette.IsCompactPalette"
second_title: "Aspose.PSD för .NET API‑referens"
description: "IColorPalette‑egenskap. Hämtar ett värde som indikerar om kompakt palett används"
type: docs
weight: 40
url: /sv/net/aspose.psd/icolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## IColorPalette.IsCompactPalette property

Hämtar ett värde som indikerar om kompakt palett används.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` om kompakt palett används; annars `false`.

## Anmärkningar

Kompakt palett innebär att bilden endast kommer att innehålla de angivna palettposterna om möjligt, med andra ord blir bilden mer kompakt och upptar mindre utrymme; annars kommer det att finnas 2^BitsPerPixel poster och bilden kommer att reservera mer utrymme för alla möjliga palettposter. Att sätta detta värde till true och ändra palettposter kan medföra prestandapåverkan eftersom dataförflyttning kan ske, så använd det försiktigt.

### Se även

* interface [IColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


