---
title: VectorShapeOriginSettings.IsOriginBoxCornersPresent
second_title: Aspose.PSD for .NET API Referansı
description: VectorShapeOriginSettings mülk. Bu örneğin kaynak kutu köşeleri özelliğine sahip olup olmadığını gösteren bir değer alır.
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

Bu örneğin kaynak kutu köşeleri özelliğine sahip olup olmadığını gösteren bir değer alır.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Mülk değeri

`doğru` bu örnek, başlangıç kutusu köşeleri özelliğine sahipse; aksi takdirde,`YANLIŞ` .

### Örnekler

Aşağıdaki kod, vektör yolları içeren bir şekil katmanlarını yeniden boyutlandırma yeteneğini gösterir.

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

### Ayrıca bakınız

* class [VectorShapeOriginSettings](../)
* ad alanı [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* toplantı [Aspose.PSD](../../../)


