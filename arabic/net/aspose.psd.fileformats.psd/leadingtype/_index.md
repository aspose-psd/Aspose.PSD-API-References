---
title: "التعداد LeadingType"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "التعداد Aspose.PSD.FileFormats.Psd.LeadingType. نوع المسافة بين الأسطر في Photoshop"
type: docs
weight: 4030
url: /ar/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

نوع التباعد في فوتوشوب (نوع المسافة بين الأسطر).

```csharp
public enum LeadingType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| BottomToBottom | `0` | المسافة من أسفل إلى أسفل. |
| TopToTop | `1` | المسافة من أعلى إلى أعلى. |

## أمثلة

الكود التالي يوضح دعم أوضاع المسافة من أسفل إلى أسفل ومن أعلى إلى أعلى من إعدادات الفقرة.

```csharp
[C#]

string input = "leadingMode.psd";
string output = "output_leadingMode.png";

using (var psdImage = (PsdImage)Image.Load(input, new PsdLoadOptions()))
{
    IText text1 = ((TextLayer)psdImage.Layers[1]).TextData;
    foreach (var textPortion in text1.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.TopToTop; // Change LeadingType value   
    }
    text1.Items[8].Text = "TopToTop";
    text1.Items[8].Style.FillColor = Color.ForestGreen;
    text1.UpdateLayerData();

    IText text2 = ((TextLayer)psdImage.Layers[2]).TextData;
    foreach (var textPortion in text2.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.BottomToBottom; // Change LeadingType value   
    }
    text2.Items[8].Text = "BottomToBottom";
    text2.Items[8].Style.FillColor = Color.ForestGreen;
    text2.UpdateLayerData();

    psdImage.Save(output, new PngOptions());
}
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


