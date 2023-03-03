---
title: TextLayer.Resize
second_title: Aspose.PSD لمرجع .NET API
description: TextLayer طريقة. يغير حجم الصورة. الافتراضيLeftTopToLeftTopيستخدم .
type: docs
weight: 90
url: /ar/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

يغير حجم الصورة. الافتراضيLeftTopToLeftTopيستخدم .

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد . |
| newHeight | Int32 | الارتفاع الجديد . |
| resizeType | ResizeType | نوع تحويل تغيير الحجم[`ResizeType`](../../../aspose.psd/resizetype/) |

### أمثلة

يوضح الكود التالي دالة TextLayer.Resize مع المعلمة لاختيار آلية تغيير الحجم.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // يضع حجمًا جديدًا لطبقة النص
    const int NewWidth = 250;
    const int NewHeight = 250;

    // يحدد آلية كيفية قيام وظيفة تغيير الحجم بتغيير حجم الطبقة (القيمة الافتراضية)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // آلية جديدة لتغيير حجم طبقة النص باستخدام هنا
    // لن يتم تغيير الطبقة فحسب ، بل سيتم تغيير مصفوفة التحويل لطبقة النص أيضًا
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // سبب دلتا هو خط افتراضي مختلف
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

### أنظر أيضا

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* المجسم [Aspose.PSD](../../../)


