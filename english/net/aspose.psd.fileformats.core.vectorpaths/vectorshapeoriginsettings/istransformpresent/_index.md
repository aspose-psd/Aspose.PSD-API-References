---
title: VectorShapeOriginSettings.IsTransformPresent
second_title: Aspose.PSD for .NET API Reference
description: VectorShapeOriginSettings property. Gets a value indicating whether this instance has the transform property
type: docs
weight: 100
url: /net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsTransformPresent property

Gets a value indicating whether this instance has the transform property.

```csharp
public bool IsTransformPresent { get; }
```

### Property Value

`true` if this instance has the transform property; otherwise, `false`.

## Examples

The following code demonstrate the ability to resize a shape layers that contains vector paths.

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

### See Also

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


