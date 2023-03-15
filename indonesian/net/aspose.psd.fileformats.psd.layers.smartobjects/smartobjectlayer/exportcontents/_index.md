---
title: SmartObjectLayer.ExportContents
second_title: Aspose.PSD untuk Referensi .NET API
description: SmartObjectLayer metode. Mengekspor konten yang disematkan atau ditautkan ke file.
type: docs
weight: 100
url: /id/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/exportcontents/
---
## SmartObjectLayer.ExportContents method

Mengekspor konten yang disematkan atau ditautkan ke file.

```csharp
public void ExportContents(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file ekspor. |

### Contoh

Kode berikut menunjukkan dukungan objek Cerdas Tertanam.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// Contoh ini menunjukkan cara mengubah lapisan objek pintar di file PSD dan mengekspor/memperbarui konten tersemat asli objek pintar.
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

        // Mari ekspor gambar objek pintar tersemat dari lapisan objek pintar PSD
        smartObjectLayer.ExportContents(exportPath);

        // Mari kita periksa apakah gambar aslinya disimpan dengan benar
        image.Save(psdOutputPath, new PsdOptions(image));
        image.Save(pngOutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

        using (var innerImage = (RasterImage)smartObjectLayer.LoadContents(null))
        {
            AssertAreEqual(format, innerImage.FileFormat);

            // Mari kita membalikkan gambar smart object asli
            var pixels = innerImage.LoadArgb32Pixels(innerImage.Bounds);
            for (int i = 0; i < pixels.Length; i++)
            {
                var pixel = pixels[i];
                var alpha = (int)(pixel & 0xff000000);
                pixels[i] = (~(pixel & 0x00ffffff)) | alpha;
            }

            innerImage.SaveArgb32Pixels(innerImage.Bounds, pixels);

            // Mari kita ganti gambar objek pintar tersemat di lapisan PSD
            smartObjectLayer.ReplaceContents(innerImage);
        }

        // Mari kita periksa apakah gambar yang diperbarui disimpan dengan benar
        image.Save(psd2OutputPath, new PsdOptions(image));
        image.Save(png2OutputPath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Lihat juga

* class [SmartObjectLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../smartobjectlayer/)
* perakitan [Aspose.PSD](../../../)


