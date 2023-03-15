---
title: TextFontInfo.Style
second_title: Aspose.PSD لمرجع .NET API
description: TextFontInfo ملكية. الحصول على نمط الخط الذي تم تحليله من اسم العائلة الفرعية
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

الحصول على نمط الخط الذي تم تحليله من اسم العائلة الفرعية

```csharp
public FontStyle Style { get; }
```

### Property_Value

تحليل نمط الخط من اسم العائلة الفرعية

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

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo/)
* المجسم [Aspose.PSD](../../../)


