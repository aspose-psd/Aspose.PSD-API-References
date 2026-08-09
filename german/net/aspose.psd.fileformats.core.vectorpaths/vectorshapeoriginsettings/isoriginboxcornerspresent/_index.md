---
title: "VectorShapeOriginSettings.IsOriginBoxCornersPresent"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "VectorShapeOriginSettings-Eigenschaft. Gibt einen Wert zurück, der angibt, ob diese Instanz die Eigenschaft für die Ecken der Ursprung-Box hat"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

Liest einen Wert, der angibt, ob diese Instanz die Eigenschaft für die Ursprungskasten-Ecken hat.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Property Value

`true`, wenn diese Instanz die Eigenschaft für die Ecken der Ursprung-Box hat; andernfalls `false`.

## Beispiele

Der folgende Code demonstriert die Fähigkeit, Shape-Layer, die Vektorpfade enthalten, zu skalieren.

```csharp
[C#]

string sourceFileName = "vectorShapes.psd";
string outputFileName = "out_vectorShapes.psd";
string sourcePath = sourceFileName;
string outputPath = outputFileName;
string outputPathPng = Path.ChangeExtension(outputPath, ".png");
using (var psdImage = (PsdImage)Image.Load(sourcePath))
{
    foreach (var layer in psdImage.Layers)
    {
        layer.Resize(layer.Width * 5 / 4, layer.Height / 2);
    }

    psdImage.Save(outputPath);
    psdImage.Save(outputPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Siehe auch

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


