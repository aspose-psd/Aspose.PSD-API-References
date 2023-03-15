---
title: TextLayer.GetFonts
second_title: Aspose.PSD لمرجع .NET API
description: TextLayer طريقة. يحصل على مجموعة الخطوط لطبقة النص.
type: docs
weight: 80
url: /ar/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
## TextLayer.GetFonts method

يحصل على مجموعة الخطوط لطبقة النص.

```csharp
public TextFontInfo[] GetFonts()
```

### قيمة الإرجاع

مجموعة الخطوط لطبقة النص.

### أمثلة

يوضح الكود التالي كيف يحصل Aspose.PSD على خصائص التنسيق المضمن لطبقة النص.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// تحميل صورة موجودة في مثيل لفئة PsdImage
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{

    var layers = psdImage.Layers;
    for (int index = 0; index < layers.Length; index++)
    {
        var layer = layers[index];
        if (!(layer is TextLayer))
        {
            continue;
        }

        var textLayer = (TextLayer)layer;

        // يحصل على الخطوط التي تحتوي على طبقة النص
        var fonts = textLayer.GetFonts();
        var textPortions = textLayer.TextData.Items;

        foreach (var textPortion in textPortions)
        {
            TextFontInfo font = fonts[textPortion.Style.FontIndex];
            if (font != null)
            {
                switch (font.Style)
                {
                    case FontStyle.Regular:
                        regularText.Add(textPortion);
                        break;
                    case FontStyle.Bold:
                        boldText.Add(textPortion);
                        break;
                    case FontStyle.Italic:
                        italicText.Add(textPortion);
                        break;
                    default:
                        throw new ArgumentOutOfRangeException();
                }
            }
        }
    }
}
```

### أنظر أيضا

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* المجسم [Aspose.PSD](../../../)


