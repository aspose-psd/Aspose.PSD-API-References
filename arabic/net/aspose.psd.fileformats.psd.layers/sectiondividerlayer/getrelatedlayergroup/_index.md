---
title: SectionDividerLayer.GetRelatedLayerGroup
second_title: Aspose.PSD لمرجع .NET API
description: SectionDividerLayer طريقة. يحصل على ملفLayerGroup هذا متعلق بهذاSectionDividerLayer المثال.
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
## SectionDividerLayer.GetRelatedLayerGroup method

يحصل على ملف[`LayerGroup`](../../layergroup/) هذا متعلق بهذا[`SectionDividerLayer`](../) المثال.

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### قيمة الإرجاع

ال[`LayerGroup`](../../layergroup/) مثال.

### أمثلة

يوضح الكود التالي طبقات SectionDividerLayer وكيفية الحصول على LayerGroup المرتبطة بها.

```csharp
[C#]

// يوضح الكود التالي طبقات SectionDividerLayer وكيفية الحصول على LayerGroup المرتبطة بها.

// طبقات التسلسل الهرمي
// [0]: '< / Layer group >' SectionDividerLayer للمجموعة 1
// [1]: الطبقة العادية "الطبقة 1"
// [2]: '< / Layer group >' SectionDividerLayer للمجموعة 2
// [3]: '< / Layer group >' SectionDividerLayer للمجموعة 3
// [4]: "Group 3" GroupLayer
// [5]: "Group 2" GroupLayer
// [6]: "Group 1" GroupLayer

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
    // إضافة LayerGroup "المجموعة 1"
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // أضف طبقة عادية
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // إضافة LayerGroup "المجموعة 2"
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // إضافة LayerGroup "المجموعة 3"
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // يحصل على SectionDividerLayer's
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // باستخدام طريقة SectionDividerLayer.GetRelatedLayerGroup () ، يحصل على مثيل LayerGroup ذي الصلة.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // نفس LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // نفس LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // نفس LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // "المجموعة 1" تحتوي على 5 طبقات
}
```

### أنظر أيضا

* class [LayerGroup](../../layergroup/)
* class [SectionDividerLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* المجسم [Aspose.PSD](../../../)


