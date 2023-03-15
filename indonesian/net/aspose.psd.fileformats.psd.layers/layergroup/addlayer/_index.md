---
title: LayerGroup.AddLayer
second_title: Aspose.PSD untuk Referensi .NET API
description: LayerGroup metode. Menambahkan layer ke grup layer.
type: docs
weight: 60
url: /id/net/aspose.psd.fileformats.psd.layers/layergroup/addlayer/
---
## LayerGroup.AddLayer method

Menambahkan layer ke grup layer.

```csharp
public void AddLayer(Layer layer)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| layer | Layer | Lapisan. |

### Contoh

Contoh berikut menunjukkan bagaimana Anda dapat menambahkan gambar Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif sebagai layer ke PsdImage

```csharp
[C#]

string outputFilePath = "PsdResult.psd";

var filesList = new string[]
{
    "PsdExample.psd",
    "BmpExample.bmp",
    "GifExample.gif",
    "Jpeg2000Example.jpf",
    "JpegExample.jpg",
    "PngExample.png",
    "TiffExample.tif",
};

using (var image = new PsdImage(200, 200))
{
    foreach (var fileName in filesList)
    {
        string filePath = fileName;
        using (var stream = new FileStream(filePath, FileMode.Open))
        {
            Layer layer = null;
            try
            {
                layer = new Layer(stream);
                image.AddLayer(layer);
            }
            catch (Exception e)
            {
                if (layer != null)
                {
                    layer.Dispose();
                }

                throw e;
            }
        }
    }

    image.Save(outputFilePath);
}
```

### Lihat juga

* class [Layer](../../layer/)
* class [LayerGroup](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* perakitan [Aspose.PSD](../../../)


