---
title: IColorPalette.IsCompactPalette
second_title: Aspose.PSD för .NET API-referens
description: IColorPalette fast egendom. Får ett värde som indikerar om kompakt palett används.
type: docs
weight: 40
url: /sv/net/aspose.psd/icolorpalette/iscompactpalette/
---
## IColorPalette.IsCompactPalette property

Får ett värde som indikerar om kompakt palett används.

```csharp
public bool IsCompactPalette { get; }
```

### Fastighetsvärde

`Sann` om kompakt palett används; annat,`falsk`.

### Anmärkningar

Kompakt palett innebär att bilden endast kommer att innehålla de angivna palettposterna om möjligt eller med andra ord blir bilden mer kompakt och tar mindre plats; annars kommer det att finnas 2^BitsPerPixel poster och bilden kommer att reservera mer utrymme för alla möjliga palettposter. Att ställa in det här värdet på sant och ändra palettposter kan orsaka prestationsstraff eftersom dataförflyttning kan inträffa så använd det försiktigt.

### Se även

* interface [IColorPalette](../)
* namnutrymme [Aspose.PSD](../../icolorpalette/)
* hopsättning [Aspose.PSD](../../../)


