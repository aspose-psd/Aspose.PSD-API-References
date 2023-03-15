---
title: Enum TextOrientation
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.TextOrientation تعداد. تعداد وضع اتجاه النص.
type: docs
weight: 4010
url: /ar/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

تعداد وضع اتجاه النص.

```csharp
public enum TextOrientation
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Horizontal | `0` | اتجاه النص الأفقي . |
| Vertical | `2` | اتجاه النص العمودي . |

### أمثلة

يوضح التعليمة البرمجية التالية القدرة على تحرير خاصية TextOrientation الجديدة. لا يؤثر هذا على العرض في الوقت الحالي ، ولكنه يسمح لك فقط بتحرير قيمة الخاصية.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // القراءة الصحيحة
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
        // القراءة الصحيحة
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* المجسم [Aspose.PSD](../../)


