---
title: "SectionDividerLayer.GetRelatedLayerGroup"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة SectionDividerLayer. يحصل على LayerGroup المرتبط بهذا المثيل من SectionDividerLayer"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
{{< psd/tize >}}
## SectionDividerLayer.GetRelatedLayerGroup method

يحصل على [`LayerGroup`](../../layergroup/) المرتبط بهذا المثيل من [`SectionDividerLayer`](../).

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### قيمة الإرجاع

مثيل [`LayerGroup`](../../layergroup/).

## أمثلة

الكود التالي يوضح طبقات SectionDividerLayer وكيفية الحصول على مجموعة LayerGroup المرتبطة بها.

```csharp
[C#]

// الكود التالي يوضح طبقات SectionDividerLayer وكيفية الحصول على مجموعة LayerGroup المرتبطة بها.

// تسلسل الطبقات
//    [0]: '</Layer group>' SectionDividerLayer للمجموعة 1
//    [1]: 'Layer 1' طبقة عادية
//    [2]: '</Layer group>' SectionDividerLayer للمجموعة 2
//    [3]: '</Layer group>' SectionDividerLayer للمجموعة 3
//    [4]: 'Group 3' GroupLayer
//    [5]: 'Group 2' GroupLayer
//    [6]: 'Group 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // إنشاء تسلسل هرمي للطبقات
    // إضافة مجموعة الطبقات 'Group 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // إضافة طبقة عادية
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // إضافة مجموعة الطبقات 'Group 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // إضافة مجموعة الطبقات 'Group 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // يحصل على SectionDividerLayer
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // باستخدام طريقة SectionDividerLayer.GetRelatedLayerGroup()، يحصل على نسخة مجموعة الطبقات المرتبطة.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### انظر أيضًا

* class [LayerGroup](../../layergroup/)
* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


