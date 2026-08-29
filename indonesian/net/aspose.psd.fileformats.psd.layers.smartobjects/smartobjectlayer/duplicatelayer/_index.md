---
title: "SmartObjectLayer.DuplicateLayer"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode SmartObjectLayer. Membuat lapisan smart object baru dengan menyalin yang ini. Perhatikan bahwa untuk smart object tersemat gambar tersemat dibagikan. Jika Anda ingin menyalin gambar tersemat, gunakan metode NewSmartObjectViaCopy."
type: docs
weight: 100
url: /id/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/duplicatelayer/
---
{{< psd/tize >}}
## SmartObjectLayer.DuplicateLayer method

Membuat lapisan objek pintar baru dengan menyalin yang ini. Perhatikan bahwa untuk objek pintar yang disematkan, gambar yang disematkan dibagikan. Jika Anda ingin menyalin gambar yang disematkan, gunakan metode [`NewSmartObjectViaCopy`](../newsmartobjectviacopy/).

```csharp
public SmartObjectLayer DuplicateLayer()
```

### Nilai Kembalian

Instansi [`SmartObjectLayer`](../) yang diklon.

## Contoh

Contoh-contoh ini menunjukkan cara menyalin lapisan smart object dalam gambar PSD.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Contoh-contoh ini menunjukkan cara menyalin lapisan smart object dalam gambar PSD.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // The layer number to copy
    string filePath = dataDir + fileName + ".psd";
    string outputFilePath = outputDir + fileName + "_copy_" + layerNumber;
    string pngOutputPath = outputFilePath + ".png";
    string psdOutputPath = outputFilePath + ".psd";
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[layerNumber];
        var newLayer = smartObjectLayer.NewSmartObjectViaCopy();
        newLayer.IsVisible = false;
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        var duplicatedLayer = smartObjectLayer.DuplicateLayer();
        duplicatedLayer.DisplayName = smartObjectLayer.DisplayName + " shared image";
        AssertIsTrue(object.ReferenceEquals(newLayer, image.Layers[layerNumber + 2]));
        AssertIsTrue(object.ReferenceEquals(duplicatedLayer, image.Layers[layerNumber + 1]));
        AssertIsTrue(object.ReferenceEquals(smartObjectLayer, image.Layers[layerNumber]));

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            // Mari balikkan gambar smart object tersemat (untuk gambar PSD internal, kita hanya membalikkan lapisan pertamanya).
            InvertImage(innerImage);

            // Mari ganti gambar objek pintar tertanam di lapisan PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Lapisan yang diduplikasi berbagi gambar tersematnya dengan smart object asli.
        // dan harus diperbarui secara eksplisit, jika tidak cache rendering‑nya tetap tidak berubah.
        // Kami memperbarui setiap smart object untuk memastikan bahwa lapisan baru yang dibuat oleh NewSmartObjectViaCopy
        // tidak berbagi gambar tersemat dengan yang lain.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Membalikkan gambar raster termasuk gambar PSD.
void InvertImage(RasterImage innerImage)
{
    var innerPsdImage = innerImage as PsdImage;
    if (innerPsdImage != null)
    {
        InvertRasterImage(innerPsdImage.Layers[0]);
    }
    else
    {
        InvertRasterImage(innerImage);
    }
}

// Membalikkan citra raster.
void InvertRasterImage(RasterImage innerImage)
{
    var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
    for (int i = 0; i < pixels.Length; i++)
    {
        var pixel = pixels[i];
        var alpha = (int)(pixel & 0xff000000);
        pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
    }

    innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);
}

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}
```

### Lihat Juga

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


