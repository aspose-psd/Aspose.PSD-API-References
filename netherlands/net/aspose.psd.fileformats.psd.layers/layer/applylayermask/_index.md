---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Layer-methode. Past het laagmasker toe op de laag en verwijdert vervolgens het masker"
type: docs
weight: 350
url: /nl/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Past het laagmasker toe op de laag en verwijdert vervolgens het masker.

```csharp
public void ApplyLayerMask()
```

## Voorbeelden

De volgende code demonstreert de functionaliteit om een masker op de laag toe te passen.

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

### Zie ook

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


