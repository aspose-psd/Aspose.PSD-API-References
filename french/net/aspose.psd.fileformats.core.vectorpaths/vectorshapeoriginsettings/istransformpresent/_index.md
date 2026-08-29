---
title: "VectorShapeOriginSettings.IsTransformPresent"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété VectorShapeOriginSettings. Obtient une valeur indiquant si cette instance possède la propriété transform"
type: docs
weight: 100
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsTransformPresent property

Obtient une valeur indiquant si cette instance possède la propriété de transformation.

```csharp
public bool IsTransformPresent { get; }
```

### Property Value

`true` si cette instance possède la propriété transform ; sinon, `false`.

## Exemples

Le code suivant démontre la capacité à redimensionner des calques de forme contenant des chemins vectoriels.

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

### Voir aussi

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


