---
title: IText.TextOrientation
second_title: Aspose.PSD لمرجع .NET API
description: IText ملكية. الحصول على أو تحديد اتجاه النص.
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

الحصول على أو تحديد اتجاه النص.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Property_Value

اتجاه النص .

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* المجسم [Aspose.PSD](../../../)


