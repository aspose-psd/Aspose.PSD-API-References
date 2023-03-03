---
title: Enum AutoKerning
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.AutoKerning enum. Mode kerning otomatis Photoshop jarak antar simbol.
type: docs
weight: 1600
url: /id/net/aspose.psd.fileformats.psd/autokerning/
---
## AutoKerning enumeration

Mode kerning otomatis Photoshop (jarak antar simbol).

```csharp
public enum AutoKerning
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Manual | `0` | Nilai kern manual. |
| Metric | `1` | Kerning metrik menggunakan pasangan kern, yang disertakan dengan sebagian besar font (dari desainernya). |
| Optical | `2` | Optical kerning menyesuaikan jarak antara karakter yang berdekatan berdasarkan bentuknya. |

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

* ruang nama [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* perakitan [Aspose.PSD](../../)


