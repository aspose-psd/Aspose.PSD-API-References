---
title: "SmartObjectLayer.LoadContents"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode SmartObjectLayer. Mendapatkan konten gambar yang tertanam atau ditautkan dari lapisan objek pintar"
type: docs
weight: 130
url: /id/net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/loadcontents/
---
{{< psd/tize >}}
## SmartObjectLayer.LoadContents method

Mendapatkan konten gambar yang tertanam atau ditautkan dari lapisan objek pintar.

```csharp
public Image LoadContents(LoadOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| opsi | LoadOptions | Opsi. |

### Nilai Kembalian

Instansi objek pintar [`Image`](../../../aspose.psd/image/) yang dimuat.

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

* class [Image](../../../aspose.psd/image/)
* class [LoadOptions](../../../aspose.psd/loadoptions/)
* class [SmartObjectLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartObjects](../../../aspose.psd.fileformats.psd.layers.smartobjects/)
* assembly [Aspose.PSD](../../../)


