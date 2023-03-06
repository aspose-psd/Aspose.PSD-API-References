---
title: Txt2Resource.AddTextRecord
second_title: Aspose.PSD for .NET API Referansı
description: Txt2Resource yöntem. Metin kaydını Kaynağa ekler ve metin kaydının kimliğini döndürür.
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
## Txt2Resource.AddTextRecord method

Metin kaydını Kaynağa ekler ve metin kaydının kimliğini döndürür.

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| text | String | Kayıt metni. |
| bounds | RectangleF | sınırlar. |

### Geri dönüş değeri

source için metin kaydının kimliğini döndürür

### istisnalar

| istisna | şart |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Bilinmeyen Txt2 Kaynak sürümü. |

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

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../txt2resource/)
* toplantı [Aspose.PSD](../../../)


