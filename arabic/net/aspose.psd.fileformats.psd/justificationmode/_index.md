---
title: Enum JustificationMode
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.JustificationMode تعداد. وضع محاذاة النص .
type: docs
weight: 1650
url: /ar/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

وضع محاذاة النص .

```csharp
public enum JustificationMode
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Left | `0` | نص محاذاة لليسار . |
| Right | `1` | نص محاذاة اليمين . |
| Center | `2` | نص المركز . |

### أمثلة

يوضح الكود التالي دعم تعداد JustificationMode لتعيين محاذاة النص لأجزاء النص.

```csharp
[C#]

string src = "source1107.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (var image = (PsdImage) Image.Load(src))
{
    var txtLayer = image.AddTextLayer("Text line1\rText line2\rText line3",
        new Rectangle(200, 200, 500, 500));
    var portions = txtLayer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Left;
    portions[1].Paragraph.Justification = JustificationMode.Right;
    portions[2].Paragraph.Justification = JustificationMode.Center;

    foreach (var portion in portions)
    {
        portion.Style.FontSize = 24;
    }

    txtLayer.TextData.UpdateLayerData();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* المجسم [Aspose.PSD](../../)


