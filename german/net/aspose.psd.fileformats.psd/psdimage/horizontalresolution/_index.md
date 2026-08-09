---
title: "PsdImage.HorizontalResolution"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage-Eigenschaft. Gibt die horizontale Auflösung in Pixel pro Zoll zurück oder legt sie für dieses PsdImage fest."
type: docs
weight: 170
url: /de/net/aspose.psd.fileformats.psd/psdimage/horizontalresolution/
---
{{< psd/tize >}}
## PsdImage.HorizontalResolution property

Gibt die horizontale Auflösung in Pixel pro Zoll zurück oder legt sie für dieses [`PsdImage`](../) fest.

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

Die horizontale Auflösung.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | ResolutionInfo-Ressource nicht gefunden und kann keine korrekte Auflösung setzen. |

## Hinweise

Der Standardwert für PSD ist 72, sodass, wenn [`ResolutionInfoResource`](../../../aspose.psd.fileformats.psd.resources/resolutioninforesource/) nicht gefunden wurde, dieser Wert zurückgegeben wird.

### Siehe auch

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


