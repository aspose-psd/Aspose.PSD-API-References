---
title: "PattResourceData.SetPattern"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PattResourceData metod. Ställer in mönsterpixelbufferten och målstorleken, uppdaterar Width / Height och lagrar data för sparande med standardkomprimeringsläget 0"
type: docs
weight: 110
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

Ställer in mönsterpixelbufferten och målstorleken, uppdaterar [`Width`](../width/) / [`Height`](../height/), och lagrar data för sparande med standardkomprimeringsläget (0).

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | Int32[] | 32‑bitspixlar i `0xAARRGGBB`‑format. |
| gränser | Rectangle | Pixelgränser för mönstret. |

### Undantag

| undantag | villkor |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Pixelarrayens längd måste vara lika med gränsområdet. |

### Se även

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


