---
title: "Antarmuka ISmartObjectLayerResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Antarmuka Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ISmartObjectLayerResource. Mendefinisikan antarmuka ISmartObjectLayerResource yang berisi informasi tentang sumber daya lapisan objek pintar dalam file PSD. Ini juga merupakan antarmuka markup yang digunakan untuk menandai sumber daya Sold dan Sole dalam gambar Adobe Photoshop."
type: docs
weight: 2830
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/
---
{{< psd/tize >}}
## ISmartObjectLayerResource interface

Mendefinisikan antarmuka ISmartObjectLayerResource yang berisi informasi tentang sumber daya lapisan objek pintar dalam file PSD. Juga merupakan antarmuka markup yang digunakan untuk menandai sumber daya Sold dan Sole dalam gambar Adobe® Photoshop®.

```csharp
public interface ISmartObjectLayerResource : IPlacedLayerResource
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [PlacedId](../../aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/placedid/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi unik data lapisan objek pintar ini dalam gambar PSD. |

## Contoh

Kode berikut menunjukkan dukungan objek pintar tertanam.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Contoh ini menunjukkan cara mengubah lapisan objek pintar dalam file PSD dan mengekspor / memperbarui konten asli objek pintar yang tertanam.
const int left = 0;
const int top = 0;
const int right = 0xb;
const int bottom = 0x10;
FileFormat[] formats = new[]
{
    FileFormat.Png, FileFormat.Psd, FileFormat.Bmp, FileFormat.Jpeg, FileFormat.Gif, FileFormat.Tiff, FileFormat.Jpeg2000
};
foreach (FileFormat format in formats)
{
    string formatString = format.ToString().ToLowerInvariant();
    string formatExt = format == FileFormat.Jpeg2000 ? "jpf" : formatString;
    string fileName = "r-embedded-" + formatString;
    string sourceFilePath = fileName + ".psd";
    string pngOutputPath = fileName + "_output.png";
    string psdOutputPath = fileName + "_output.psd";
    string png2OutputPath = fileName + "_updated.png";
    string psd2OutputPath = fileName + "_updated.psd";
    string exportPath = fileName + "_export." + formatExt;
    using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
    {
        var smartObjectLayer = (SmartObjectLayer)image.Layers[0];

        AssertAreEqual(left, smartObjectLayer.ContentsBounds.Left);
        AssertAreEqual(top, smartObjectLayer.ContentsBounds.Top);
        AssertAreEqual(right, smartObjectLayer.ContentsBounds.Right);
        AssertAreEqual(bottom, smartObjectLayer.ContentsBounds.Bottom);

        // Mari ekspor gambar objek pintar tertanam dari lapisan objek pintar PSD
        smartObjectLayer.ExportContents(exportPath);

        // Mari periksa apakah gambar asli disimpan dengan benar
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Mari balikkan gambar objek pintar asli
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Mari ganti gambar objek pintar tertanam di lapisan PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Mari periksa apakah gambar yang diperbarui disimpan dengan benar
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Lihat Juga

* interface [IPlacedLayerResource](../iplacedlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


