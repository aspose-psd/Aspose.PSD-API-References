---
title: "PattResourceData.SetPattern"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PattResourceData-Methode. Setzt den Pixelpuffer des Musters und die Zielgröße, aktualisiert Width / Height und speichert die Daten zum Speichern unter Verwendung des Standardkomprimierungsmodus 0"
type: docs
weight: 110
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

Setzt den Pixelpuffer des Musters und die Zielgröße, aktualisiert [`Width`](../width/) / [`Height`](../height/), und speichert die Daten zum Speichern unter Verwendung des Standardkomprimierungsmodus (0).

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | Int32[] | 32‑Bit‑Pixel im `0xAARRGGBB`‑Format. |
| bounds | Rectangle | Pixelgrenzen des Musters. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Die Länge des Pixelarrays muss gleich der Fläche der Grenzen sein. |

### Siehe auch

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


