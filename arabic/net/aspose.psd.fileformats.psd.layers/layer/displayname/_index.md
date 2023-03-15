---
title: Layer.DisplayName
second_title: Aspose.PSD لمرجع .NET API
description: Layer ملكية. الحصول على أو تحديد اسم عرض الطبقة.
type: docs
weight: 100
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

الحصول على أو تحديد اسم عرض الطبقة.

```csharp
public string DisplayName { get; set; }
```

### Property_Value

اسم عرض الطبقة .

### أمثلة

يوضح المثال التالي القدرة على تعيين قيمة DisplayName ، في ما يعرضه اسم الطبقة بشكل صحيح.

```csharp
[C#]

// إجراء تغييرات في أسماء الطبقات وحفظها
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

### أنظر أيضا

* class [Layer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* المجسم [Aspose.PSD](../../../)


