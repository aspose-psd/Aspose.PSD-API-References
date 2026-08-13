---
title: "VectorShapeOriginSettings.IsOriginBoxCornersPresent"
second_title: "Aspose.PSD for .NET API Referansı"
description: "VectorShapeOriginSettings özelliği. Bu örneğin orijinal kutu köşeleri özelliğine sahip olup olmadığını gösteren bir değeri alır"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

Bu örneğin orijin kutusu köşeleri özelliğine sahip olup olmadığını gösteren bir değeri alır.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Property Value

`true` eğer bu örnek orijinal kutu köşeleri özelliğine sahipse; aksi takdirde, `false`.

## Örnekler

Aşağıdaki kod, vektör yolları içeren şekil katmanlarını yeniden boyutlandırma yeteneğini gösterir.

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

### Ayrıca Bakınız

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


