---
title: "IText.TextOrientation"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية IText. تحصل أو تعيّن اتجاه النص"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
{{< psd/tize >}}
## IText.TextOrientation property

يحصل أو يضبط اتجاه النص.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Property Value

اتجاه النص.

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


