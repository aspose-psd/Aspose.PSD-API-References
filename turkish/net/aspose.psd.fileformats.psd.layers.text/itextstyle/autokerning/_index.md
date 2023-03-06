---
title: ITextStyle.AutoKerning
second_title: Aspose.PSD for .NET API Referansı
description: ITextStyle mülk. Otomatik karakter aralığını alır veya ayarlar.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.text/itextstyle/autokerning/
---
## ITextStyle.AutoKerning property

Otomatik karakter aralığını alır veya ayarlar.

```csharp
public AutoKerning AutoKerning { get; set; }
```

### Mülk değeri

İki karakter arasındaki otomatik karakter aralığı.

### Örnekler

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

### Ayrıca bakınız

* enum [AutoKerning](../../../aspose.psd.fileformats.psd/autokerning/)
* interface [ITextStyle](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* toplantı [Aspose.PSD](../../../)


