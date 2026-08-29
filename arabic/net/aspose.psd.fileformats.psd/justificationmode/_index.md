---
title: "تعداد JustificationMode"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "تعداد Aspose.PSD.FileFormats.Psd.JustificationMode enum. وضع محاذاة النص"
type: docs
weight: 1690
url: /ar/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

وضع محاذاة النص.

```csharp
public enum JustificationMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Left | `0` | محاذاة النص إلى اليسار. في وضع من اليسار إلى اليمين، الموضع Left هو Left. في وضع من اليمين إلى اليسار، الموضع Left هو Right. |
| Right | `1` | محاذاة النص إلى اليمين. في وضع من اليسار إلى اليمين، الموضع Right هو Right. في وضع من اليمين إلى اليسار، الموضع Right هو Left. |
| Center | `2` | نص مركزي. |

## أمثلة

الكود التالي يوضح دعم تعداد JustificationMode لتعيين محاذاة النص لأجزاء النص.

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

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


