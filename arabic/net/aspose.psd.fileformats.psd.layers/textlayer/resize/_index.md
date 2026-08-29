---
title: "TextLayer.Resize"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة TextLayer. تغير حجم الصورة. يتم استخدام الافتراضي LeftTopToLeftTop"
type: docs
weight: 100
url: /ar/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

يغيّر حجم الصورة. يتم استخدام الافتراضي LeftTopToLeftTop.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تحويل التحجيم [`ResizeType`](../../../aspose.psd/resizetype/) |

## أمثلة

الكود التالي يوضح وظيفة TextLayer.Resize مع المعامل لاختيار آلية التحجيم.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // يضبط الحجم الجديد لطبقة النص
    const int NewWidth = 250;
    const int NewHeight = 250;

    // يضبط الآلية التي ستستخدمها وظيفة التحجيم لتغيير حجم الطبقة (القيمة الافتراضية)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // آلية جديدة للتحجيم لطبقة النص تُستخدم هنا
    // ليس فقط الطبقة بل أيضاً مصفوفة التحويل لطبقة النص ستتغير
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // سبب الفرق هو خط افتراضي مختلف
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // كل شيء على ما يرام
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### انظر أيضًا

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


