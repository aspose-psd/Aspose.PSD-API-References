---
title: SmartObjectProvider.NewSmartObjectViaCopy
second_title: Aspose.PSD untuk Referensi .NET API
description: SmartObjectProvider metode. Membuat layer smart object baru dengan menyalin layer sumber.
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd/smartobjectprovider/newsmartobjectviacopy/
---
## SmartObjectProvider.NewSmartObjectViaCopy method

Membuat layer smart object baru dengan menyalin layer sumber.

```csharp
public SmartObjectLayer NewSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| sourceLayer | SmartObjectLayer | Lapisan sumber. |

### Nilai Pengembalian

Yang dikloning[`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) contoh.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Anda hanya dapat mengganti objek pintar yang disematkan. |

### Contoh

Contoh-contoh ini menunjukkan cara menyalin lapisan objek pintar dalam gambar PSD.

```csharp
[C#]

string dataDir = baseFolder + Path.DirectorySeparatorChar;
string outputDir = dataDir + "output" + Path.DirectorySeparatorChar;

// Contoh ini mendemonstrasikan cara menyalin layer smart object di gambar PSD.
ExampleOfCopingSmartObjectLayer("r-embedded-psd");
ExampleOfCopingSmartObjectLayer("r-embedded-png");
ExampleOfCopingSmartObjectLayer("r-embedded-transform");
ExampleOfCopingSmartObjectLayer("new_panama-papers-8-trans4");

void ExampleOfCopingSmartObjectLayer(string fileName)
{
    int layerNumber = 0; // Nomor lapisan yang akan disalin
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
            // Mari kita balikkan gambar objek pintar yang disematkan (untuk gambar PSD bagian dalam, kita hanya membalikkan lapisan pertamanya)
            InvertImage(innerImage);

            // Mari kita ganti gambar objek pintar tersemat di lapisan PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Lapisan yang digandakan berbagi gambar yang disematkan dengan objek pintar asli
        // dan itu harus diperbarui secara eksplisit jika tidak, cache renderingnya tetap tidak berubah.
        // Kami memperbarui setiap objek pintar untuk memastikan bahwa lapisan baru dibuat oleh NewSmartObjectViaCopy
        // tidak membagikan gambar tersemat dengan yang lain.
        image.SmartObjectProvider.UpdateAllModifiedContent();

        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
        image.Save(psdOutputPath, new PsdOptions(image));
    }
}

// Membalik gambar raster termasuk gambar PSD.
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

// Membalik gambar raster.
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

### Lihat juga

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* ruang nama [Aspose.PSD.FileFormats.Psd](../../smartobjectprovider/)
* perakitan [Aspose.PSD](../../../)


