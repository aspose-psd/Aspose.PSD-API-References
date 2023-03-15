---
title: RasterCachedImage.Crop
second_title: Aspose.PSD untuk Referensi .NET API
description: RasterCachedImage metode. Memotong gambar.
type: docs
weight: 90
url: /id/net/aspose.psd/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

Memotong gambar.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| rectangle | Rectangle | Persegi panjang. |

### Contoh

Kode berikut menunjukkan kemampuan untuk memotong gambar dengan persegi panjang tertentu.

```csharp
[C#]

string sourceFileName = "SourceFile.psd";
string exportPath = "SourceFileEdited.psd";
string exportPathPng = "SourceFileEdited.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    var oldLayer = image.Layers[0];
    var oldBounds = oldLayer.Bounds;

    var oldLayerData = image.Layers[0].LoadArgb32Pixels(oldBounds);

    var layers = new Layer[4];
    for (int i = 0; i < 4; i++)
    {
        layers[i] = new Layer(
            oldBounds,
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            new byte[oldBounds.Width * oldBounds.Height],
            "Layer " + i.ToString());
        layers[i].SaveArgb32Pixels(oldBounds, oldLayerData);
    }

    image.Resize(186, 602);

    layers[0].Crop(new Rectangle(0, 0, 186, 159));
    layers[1].Crop(new Rectangle(186, 0, 186, 159));
    layers[2].Crop(new Rectangle(0, 159, 186, 142));
    layers[3].Crop(new Rectangle(186, 159, 186, 142));

    oldLayer.Dispose();
    image.Layers = layers;

    var top = 0;
    for (int i = 0; i < 4; i++)
    {
        var width = layers[i].Width;
        var height = layers[i].Height;
        layers[i].Left = 0;
        layers[i].Top = top;
        layers[i].Right = width;
        layers[i].Bottom = height + layers[i].Top;
        top += layers[i].Height;
    }

    // Simpan psd
    image.Save(exportPath, new PsdOptions());

    // Simpan png
    image.Save(exportPathPng, new PngOptions());
}
```

### Lihat juga

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* ruang nama [Aspose.PSD](../../rastercachedimage/)
* perakitan [Aspose.PSD](../../../)


