---
title: "التعداد TextOrientation"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "التعداد Aspose.PSD.FileFormats.Psd.TextOrientation. تعداد وضعية توجيه النص"
type: docs
weight: 4480
url: /ar/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

تعداد لوضع توجيه النص.

```csharp
public enum TextOrientation
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Horizontal | `0` | توجيه النص الأفقي. |
| Vertical | `2` | توجيه النص العمودي. |

## أمثلة

الكود التالي يوضح القدرة على تعديل خاصية TextOrientation الجديدة. هذا لا يؤثر على العرض في الوقت الحالي، بل يسمح فقط بتعديل قيمة الخاصية.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // قراءة صحيحة
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // قراءة صحيحة
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


