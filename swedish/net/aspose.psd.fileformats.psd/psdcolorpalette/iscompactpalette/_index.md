---
title: PsdColorPalette.IsCompactPalette
second_title: Aspose.PSD för .NET API-referens
description: PsdColorPalette fast egendom. Får ett värde som indikerar om paletten är kompakt.
type: docs
weight: 70
url: /sv/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
## PsdColorPalette.IsCompactPalette property

Får ett värde som indikerar om paletten är kompakt.

```csharp
public bool IsCompactPalette { get; }
```

### Fastighetsvärde

`Sann` om kompakt det palett; annat,`falsk`.

### Anmärkningar

Kompakt palett betyder att bilden endast kommer att innehålla de angivna palettposterna om möjligt eller med andra ord blir bilden mer kompakt och tar mindre plats; annars kommer det att finnas 2^BitsPerPixel poster och bilden kommer att reservera mer utrymme för alla möjliga palettposter . Om du ställer in detta värde på sant och ändrar palettposter kan det leda till prestationsstraff eftersom datarörelser kan inträffa så använd det försiktigt.

### Se även

* class [PsdColorPalette](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdcolorpalette/)
* hopsättning [Aspose.PSD](../../../)


