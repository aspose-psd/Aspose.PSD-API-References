---
title: "ITextStyle.FontIndex"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية ITextStyle. يحصل على فهرس الخط"
type: docs
weight: 110
url: /ar/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
{{< psd/tize >}}
## ITextStyle.FontIndex property

يحصل على فهرس الخط.

```csharp
public int FontIndex { get; }
```

### Property Value

الخط.

## أمثلة

الكود التالي يوضح كيف يحصل Aspose.PSD على خصائص التنسيق المضمن لطبقة النص.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// حمّل صورة موجودة إلى مثال من فئة PsdImage
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

        // يحصل على الخطوط الموجودة في طبقة النص
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

### انظر أيضًا

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


