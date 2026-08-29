---
title: "LayerGroup.IsOpen"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية LayerGroup. تحصل أو تعيّن ما إذا كان المجلد مفتوحًا؛ إذا تم تعيينه إلى true فإن المجموعة ستكون في حالة مفتوحة عند بدء التشغيل وإلا ستكون في حالة مصغرة."
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

يحصل أو يعيّن ما إذا كان المجلد مفتوحًا؛ إذا تم تعيينه إلى `true` فإن المجموعة ستكون في حالة مفتوحة عند بدء التشغيل، وإلا ستكون في حالة مصغرة.

```csharp
public bool IsOpen { get; set; }
```

## أمثلة

الكود التالي يوضح كيفية فتح وإغلاق LayerGroup (المجلد) باستخدام خاصية IsOpen.

```csharp
[C#]

// مثال على قراءة وكتابة خاصية IsOpen أثناء التشغيل.
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### انظر أيضًا

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


