---
title: VectorShapeOriginSettings.IsTransformPresent
second_title: Aspose.PSD für .NET-API-Referenz
description: VectorShapeOriginSettings eigendom. Ruft einen Wert ab der angibt ob diese Instanz die Transformationseigenschaft hat.
type: docs
weight: 100
url: /de/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
## VectorShapeOriginSettings.IsTransformPresent property

Ruft einen Wert ab, der angibt, ob diese Instanz die Transformationseigenschaft hat.

```csharp
public bool IsTransformPresent { get; }
```

### Eigentumswert

`WAHR` wenn diese Instanz die transform-Eigenschaft hat; ansonsten,`FALSCH` .

### Beispiele

Der folgende Code demonstriert die Möglichkeit, die Größe einer Formebene zu ändern, die Vektorpfade enthält.

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
* namensraum [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* Montage [Aspose.PSD](../../../)


