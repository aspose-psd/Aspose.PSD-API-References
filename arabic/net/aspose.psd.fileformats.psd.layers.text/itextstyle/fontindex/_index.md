---
title: ITextStyle.FontIndex
second_title: Aspose.PSD لمرجع .NET API
description: ITextStyle ملكية. يحصل على فهرس الخط.
type: docs
weight: 110
url: /ar/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
## ITextStyle.FontIndex property

يحصل على فهرس الخط.

```csharp
public int FontIndex { get; }
```

### Property_Value

الخط.

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

* interface [ITextStyle](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* المجسم [Aspose.PSD](../../../)


