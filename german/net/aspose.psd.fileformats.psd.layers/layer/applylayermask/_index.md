---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Layer-Methode. Wendet die Ebenenmaske auf die Ebene an und löscht anschließend die Maske"
type: docs
weight: 350
url: /de/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Wendet die Ebenenmaske auf die Ebene an und löscht dann die Maske.

```csharp
public void ApplyLayerMask()
```

## Beispiele

Der folgende Code demonstriert die Funktion, eine Maske auf die Ebene anzuwenden.

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

### Siehe auch

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


