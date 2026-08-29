---
title: "Txt2Resource.AddTextRecord"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Txt2Resource. تضيف سجل النص إلى Resource وتعيد معرف سجل النص"
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/addtextrecord/
---
{{< psd/tize >}}
## Txt2Resource.AddTextRecord method

يضيف سجل النص إلى المورد ويعيد معرف سجل النص.

```csharp
public int AddTextRecord(string text, RectangleF bounds)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | String | نص السجل. |
| الحدود | RectangleF | الحدود. |

### قيمة الإرجاع

يعيد معرف سجل النص للمورد

### استثناءات

| استثناء | شرط |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | إصدار Txt2 Resource غير معروف. |

## أمثلة

الكود التالي يوضح دعم خصائص ITextStyle الجديدة.

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

// تحقق من القيم
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

### انظر أيضًا

* struct [RectangleF](../../../aspose.psd/rectanglef/)
* class [Txt2Resource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


