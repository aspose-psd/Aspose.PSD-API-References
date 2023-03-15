---
title: Txt2Resource.AddTextRecord
second_title: Aspose.PSD untuk Referensi .NET API
description: Txt2Resource metode. Menambahkan rekaman teks ke Sumber Daya dan mengembalikan id rekaman teks.
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
## Txt2Resource.AddTextRecord method

Menambahkan rekaman teks ke Sumber Daya dan mengembalikan id rekaman teks.

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| text | String | Teks rekaman. |
| bounds | RectangleF | Batas-batas. |

### Nilai Pengembalian

Mengembalikan ID rekaman teks untuk resource

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Versi Sumber Daya Txt2 tidak diketahui. |

### Contoh

Kode berikut menunjukkan dukungan dari dukungan properti ITextStyle baru.

```csharp
[C#]

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

string srcFile = "A.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile))
{
    var textLayer = (TextLayer)psdImage.Layers[1];
    textLayer.UpdateText("abc");

    psdImage.Save(outputFile);
}

// Periksa nilai
using (var srcImage = (PsdImage)Image.Load(srcFile))
{
    var srcTextLayer = (TextLayer)srcImage.Layers[1];
    var etalonStyle = srcTextLayer.TextData.Items[0].Style;

    using (var outImage = (PsdImage)Image.Load(outputFile))
    {
        var outTextLayer = (TextLayer)outImage.Layers[1];
        var resultStyle = outTextLayer.TextData.Items[0].Style;

        AssertAreEqual(etalonStyle.AutoLeading, resultStyle.AutoLeading);
        AssertAreEqual(etalonStyle.FontIndex, resultStyle.FontIndex);
        AssertAreEqual(etalonStyle.Underline, resultStyle.Underline);
        AssertAreEqual(etalonStyle.Strikethrough, resultStyle.Strikethrough);
        AssertAreEqual(etalonStyle.AutoKerning, resultStyle.AutoKerning);
        AssertAreEqual(etalonStyle.StandardLigatures, resultStyle.StandardLigatures);
        AssertAreEqual(etalonStyle.DiscretionaryLigatures, resultStyle.DiscretionaryLigatures);
        AssertAreEqual(etalonStyle.ContextualAlternates, resultStyle.ContextualAlternates);
        AssertAreEqual(etalonStyle.LanguageIndex, resultStyle.LanguageIndex);
        AssertAreEqual(etalonStyle.VerticalScale, resultStyle.VerticalScale);
        AssertAreEqual(etalonStyle.HorizontalScale, resultStyle.HorizontalScale);
        AssertAreEqual(etalonStyle.Fractions, resultStyle.Fractions);
    }
}
```

### Lihat juga

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../txt2resource/)
* perakitan [Aspose.PSD](../../../)


