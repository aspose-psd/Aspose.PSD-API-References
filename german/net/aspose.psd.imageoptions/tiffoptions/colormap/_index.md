---
title: TiffOptions.ColorMap
second_title: Aspose.PSD für .NET-API-Referenz
description: TiffOptions eigendom. Ruft die Farbkarte ab oder legt sie fest.
type: docs
weight: 70
url: /de/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

Ruft die Farbkarte ab oder legt sie fest.

```csharp
public ushort[] ColorMap { get; set; }
```

### Eigentumswert

Die Farbkarte.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wert |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | Die Farbtabelle kann nur für Samples pro Pixel gleich 1 definiert werden. oder Die Bits pro Sample sind nicht definiert. |
| ArgumentOutOfRangeException | value;Die Arraylänge muss folgender Formel entsprechen: 3 * (2**BitsPerSample). |

### Siehe auch

* class [TiffOptions](../)
* namensraum [Aspose.PSD.ImageOptions](../../tiffoptions/)
* Montage [Aspose.PSD](../../../)


