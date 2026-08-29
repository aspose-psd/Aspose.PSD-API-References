---
title: "AiImage.SetPalette"
second_title: "Aspose.PSD för .NET API‑referens"
description: "AiImage-metod. Ställer in bildpaletten."
type: docs
weight: 200
url: /sv/net/aspose.psd.fileformats.ai/aiimage/setpalette/
---
{{< psd/tize >}}
## AiImage.SetPalette method

Ställer in bildpaletten.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palett | IColorPalette | Paletten att sätta. |
| updateColors | Boolean | om den är satt till `true` uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan få bilden att krascha vid inläsning om vissa index saknar motsvarande palettposter. |

### Undantag

| undantag | villkor |
| --- | --- |
| NotImplementedException | Ej implementerad |

### Se även

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


