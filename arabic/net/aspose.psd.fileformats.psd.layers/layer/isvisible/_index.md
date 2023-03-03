---
title: Layer.IsVisible
second_title: Aspose.PSD لمرجع .NET API
description: Layer ملكية. الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الطبقة مرئية
type: docs
weight: 170
url: /ar/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الطبقة مرئية

```csharp
public bool IsVisible { get; set; }
```

### Property_Value

`حقيقي` إذا كان هذا المثال مرئيًا ؛ خلاف ذلك،`خطأ شنيع` .

### أمثلة

يوضح المثال التالي كيف يمكنك تغيير رؤية LayerGroup في Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// إجراء تغييرات في أسماء الطبقات وحفظها
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // قم بإيقاف تشغيل كل شيء داخل المجموعة
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### أنظر أيضا

* class [Layer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* المجسم [Aspose.PSD](../../../)


