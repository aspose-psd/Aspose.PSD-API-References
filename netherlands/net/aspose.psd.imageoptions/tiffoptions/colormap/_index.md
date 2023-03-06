---
title: TiffOptions.ColorMap
second_title: Aspose.PSD voor .NET API-referentie
description: TiffOptions eigendom. Haalt of stelt de kleurenkaart in.
type: docs
weight: 70
url: /nl/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

Haalt of stelt de kleurenkaart in.

```csharp
public ushort[] ColorMap { get; set; }
```

### Eigendoms-waarde

De kleurenkaart.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | waarde |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | De kleurenkaart kan alleen worden gedefinieerd voor samples per pixel gelijk aan 1. or De bits per sample zijn niet gedefinieerd. |
| ArgumentOutOfRangeException | waarde; De arraylengte moet overeenkomen met de volgende formule: 3 * (2**BitsPerSample). |

### Zie ook

* class [TiffOptions](../)
* naamruimte [Aspose.PSD.ImageOptions](../../tiffoptions/)
* montage [Aspose.PSD](../../../)


