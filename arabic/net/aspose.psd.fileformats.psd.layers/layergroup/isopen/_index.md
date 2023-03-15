---
title: LayerGroup.IsOpen
second_title: Aspose.PSD لمرجع .NET API
description: LayerGroup ملكية. Gets أو المجموعات هو المجلد المفتوح إذا تم تعيينه علىحقيقي من المجموعة ستكون في حالة مفتوحة عند بدء التشغيل  وإلا في حالة مصغرة.
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

Gets أو المجموعات هو المجلد المفتوح إذا تم تعيينه على`حقيقي` من المجموعة ستكون في حالة مفتوحة عند بدء التشغيل ، وإلا في حالة مصغرة.

```csharp
public bool IsOpen { get; set; }
```

### أمثلة

توضح التعليمات البرمجية التالية كيفية فتح وإغلاق LayerGroup (مجلد) باستخدام خاصية IsOpen.

```csharp
[C#]

// مثال على قراءة وكتابة خاصية IsOpen في وقت التشغيل.
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

### أنظر أيضا

* class [LayerGroup](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* المجسم [Aspose.PSD](../../../)


