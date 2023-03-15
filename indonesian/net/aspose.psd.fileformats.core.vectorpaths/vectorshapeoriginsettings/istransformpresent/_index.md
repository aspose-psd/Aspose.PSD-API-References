---
title: VectorShapeOriginSettings.IsTransformPresent
second_title: Aspose.PSD untuk Referensi .NET API
description: VectorShapeOriginSettings Properti. Mendapat nilai yang menunjukkan apakah instance ini memiliki properti transform.
type: docs
weight: 100
url: /id/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
## VectorShapeOriginSettings.IsTransformPresent property

Mendapat nilai yang menunjukkan apakah instance ini memiliki properti transform.

```csharp
public bool IsTransformPresent { get; }
```

### Nilai properti

`BENAR` jika instance ini memiliki properti transform; jika tidak,`PALSU` .

### Contoh

Kode berikut menunjukkan kemampuan untuk mengubah ukuran layer bentuk yang berisi jalur vektor.

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

### Lihat juga

* class [VectorShapeOriginSettings](../)
* ruang nama [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* perakitan [Aspose.PSD](../../../)


