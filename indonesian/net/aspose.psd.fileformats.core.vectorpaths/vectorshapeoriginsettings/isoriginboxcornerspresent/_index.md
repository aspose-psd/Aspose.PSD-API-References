---
title: "VectorShapeOriginSettings.IsOriginBoxCornersPresent"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti VectorShapeOriginSettings. Mendapatkan nilai yang menunjukkan apakah instance ini memiliki properti sudut kotak asal"
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

Mendapatkan nilai yang menunjukkan apakah instance ini memiliki properti sudut kotak asal.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Property Value

`true` jika instance ini memiliki properti sudut kotak asal; sebaliknya, `false`.

## Contoh

Kode berikut menunjukkan kemampuan untuk mengubah ukuran lapisan bentuk yang berisi jalur vektor.

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

### Lihat Juga

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


