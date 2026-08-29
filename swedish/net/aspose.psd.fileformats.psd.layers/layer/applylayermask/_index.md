---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Lagermetod. Tillämpar lagermasken på lagret och tar sedan bort masken"
type: docs
weight: 350
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Applicerar lagermasken på lagret, och tar sedan bort masken.

```csharp
public void ApplyLayerMask()
```

## Exempel

Följande kod demonstrerar funktionen att tillämpa mask på lagret.

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Se även

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


