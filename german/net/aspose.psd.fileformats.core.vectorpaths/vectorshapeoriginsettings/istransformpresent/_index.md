---
title: "VectorShapeOriginSettings.IsTransformPresent"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "VectorShapeOriginSettings Eigenschaft. Gibt einen Wert zurück, der angibt, ob diese Instanz die Transformations-Eigenschaft besitzt"
type: docs
weight: 100
url: /de/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsTransformPresent property

Liest einen Wert, der angibt, ob diese Instanz die Transformations‑Eigenschaft hat.

```csharp
public bool IsTransformPresent { get; }
```

### Property Value

`true` wenn diese Instanz die Transformations-Eigenschaft hat; andernfalls `false`.

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


