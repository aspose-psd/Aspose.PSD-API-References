---
title: "Enum AutoKerning"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.AutoKerning enum. Photoshop otomatik kerning modu, semboller arasındaki mesafe"
type: docs
weight: 1610
url: /tr/net/aspose.psd.fileformats.psd/autokerning/
---
{{< psd/tize >}}
## AutoKerning enumeration

Photoshop otomatik kerning modu (semboller arasındaki mesafe).

```csharp
public enum AutoKerning
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Manual | `0` | Manuel kerning değeri. |
| Metric | `1` | Metrik kerning, çoğu fontta (tasarımcılarından) bulunan kern çiftlerini kullanır. |
| Optical | `2` | Optik kerning, yan yana karakterler arasındaki boşluğu şekillerine göre ayarlar. |

## Örnekler

Aşağıdaki kod, yeni ITextStyle özelliklerinin desteğini gösterir.

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

// Değerleri kontrol et
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

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


