---
title: "Layer.DisplayName"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية Layer. تحصل على أو تعيين الاسم المعروض للطبقة"
type: docs
weight: 110
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

يحصل أو يعيّن الاسم المعروض للطبقة.

```csharp
public string DisplayName { get; set; }
```

### Property Value

الاسم المعروض للطبقة.

## أمثلة

المثال التالي يوضح القدرة على تعيين قيمة DisplayName، بحيث يتم عرض اسم الطبقة بشكل صحيح.

```csharp
[C#]

// قم بإجراء تغييرات على أسماء الطبقات واحفظها.
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // تعيين قيمة جديدة في خاصية DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### انظر أيضًا

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


