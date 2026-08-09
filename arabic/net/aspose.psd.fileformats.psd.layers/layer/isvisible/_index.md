---
title: "Layer.IsVisible"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية Layer. تحصل أو تعين قيمة تشير إلى ما إذا كانت الطبقة مرئية."
type: docs
weight: 180
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

يحصل أو يضبط قيمة تشير إلى ما إذا كانت الطبقة مرئية

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` إذا كان هذا المثيل مرئياً؛ وإلا `false`.

## أمثلة

المثال التالي يوضح كيفية تغيير رؤية LayerGroup في Aspose.PSD.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// قم بإجراء تغييرات على أسماء الطبقات واحفظها.
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // إيقاف تشغيل كل شيء داخل مجموعة.
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### انظر أيضًا

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


