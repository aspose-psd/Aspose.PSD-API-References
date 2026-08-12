---
title: "VectorShapeOriginSettings.IsOriginBoxCornersPresent"
second_title: "Справочник API Aspose.PSD для .NET"
description: "VectorShapeOriginSettings свойство. Получает значение, указывающее, имеет ли данный экземпляр свойство углов исходного прямоугольника"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

Получает значение, указывающее, имеет ли этот экземпляр свойство углов исходного коробочного прямоугольника.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Property Value

`true` если данный экземпляр имеет свойство углов исходного прямоугольника; иначе `false`.

## Примеры

Следующий код демонстрирует возможность изменения размера слоёв формы, содержащих векторные пути.

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

### См. также

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


