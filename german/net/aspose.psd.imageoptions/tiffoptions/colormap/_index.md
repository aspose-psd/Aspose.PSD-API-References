---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "TiffOptions-Eigenschaft. Liest oder setzt die Farbkarte"
type: docs
weight: 70
url: /de/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

Liest oder setzt die Farbkarte.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

Die Farbkarte.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wert |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | Die Farbkarte darf nur definiert werden, wenn Samples per Pixel gleich 1 ist. oder Die Bits pro Sample sind nicht definiert. |
| ArgumentOutOfRangeException | value;Die Array-Länge muss der folgenden Formel entsprechen: 3 * (2**BitsPerSample). |

### Siehe auch

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


