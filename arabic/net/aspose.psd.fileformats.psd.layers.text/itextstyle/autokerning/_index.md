---
title: ITextStyle.AutoKerning
second_title: Aspose.PSD لمرجع .NET API
description: ITextStyle ملكية. الحصول على تقنين الأحرف التلقائي أو تعيينه .
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.text/itextstyle/autokerning/
---
## ITextStyle.AutoKerning property

الحصول على تقنين الأحرف التلقائي أو تعيينه .

```csharp
public AutoKerning AutoKerning { get; set; }
```

### Property_Value

تقنين الأحرف التلقائي بين حرفين .

### أمثلة

يوضح الكود التالي دعم دعم خصائص ITextStyle الجديدة.

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

### أنظر أيضا

* enum [AutoKerning](../../../aspose.psd.fileformats.psd/autokerning/)
* interface [ITextStyle](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* المجسم [Aspose.PSD](../../../)


