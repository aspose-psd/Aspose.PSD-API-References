---
title: "SmartObjectLayer.Contents"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti SmartObjectLayer. Mendapatkan atau mengatur konten lapisan objek pintar. Konten objek pintar yang disematkan adalah file gambar mentah yang disematkan Data dan propertinya. Konten objek pintar yang ditautkan adalah konten mentah dari file gambar yang ditautkan jika tersedia dan propertinya LiFeDataSource. Kami tidak mendukung pemuatan dari Adobe Photoshop Graphics Library ketika IsLibraryLink bernilai true. Untuk file tautan biasa, pertama kami menggunakan RelativePath untuk mencari file secara relatif terhadap jalur gambar sumber SourceImagePath; jika tidak tersedia, kami mencari di FullPath; jika masih tidak ada, kami mencari file tautan di direktori yang sama dengan gambar kami SourceImagePath."
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/contents/
---
{{< psd/tize >}}
## SmartObjectLayer.Contents property

Mendapatkan atau mengatur konten lapisan objek pintar. Konten objek pintar yang disematkan adalah file gambar mentah yang disematkan: [`Data`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) dan propertinya. Konten objek pintar yang ditautkan adalah konten mentah dari file gambar yang ditautkan jika tersedia dan propertinya: [`LiFeDataSource`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/). Kami tidak mendukung pemuatan dari Adobe� Photoshop� �� Graphics Library ketika [`IsLibraryLink`](../../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) bernilai true. Untuk file tautan biasa, pertama kami menggunakan [`RelativePath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath/) untuk mencari file secara relatif terhadap jalur gambar sumber SourceImagePath; jika tidak tersedia, kami mencari di [`FullPath`](../../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath/); jika masih tidak ada, kami mencari file tautan di direktori yang sama dengan gambar kami: SourceImagePath.

```csharp
public byte[] Contents { get; set; }
```

### Property Value

Konten lapisan objek pintar byte[].

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| NotSupportedException | Tidak dapat mengambil konten dari perpustakaan Adobe Photoshop. |

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

* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


