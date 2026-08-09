---
title: "LayerGroup.AddLayerGroup"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة LayerGroup. يضيف مجموعة الطبقة"
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
{{< psd/tize >}}
## LayerGroup.AddLayerGroup method

يضيف مجموعة الطبقة.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| groupName | String | اسم المجموعة. |
| فهرس | Int32 | فهرس الطبقة التي سيتم الإدراج بعدّها. |

### قيمة الإرجاع

فتح طبقة المجموعة

## أمثلة

المثال التالي يوضح إضافة LayerGroup إلى LayerGroup آخر.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// إنشاء تسلسل طبقات كهذا:
// -المجموعة 1
// --الطبقة 1
// --المجموعة 2
// ---الطبقة 2
// ---الطبقة 3
// --الطبقة 4

var createOptions = new PsdOptions();
createOptions.Source = new FileCreateSource(sourceFileName, false);
createOptions.Palette = new PsdColorPalette(new Color[] { Color.Green });

using (var psdImage = (PsdImage)Image.Create(createOptions, 500, 500))
{
    LayerGroup group1 = psdImage.AddLayerGroup("Group 1", 0, false);

    Layer layer1 = new Layer(psdImage);
    layer1.Name = "Layer 1";
    group1.AddLayer(layer1);

    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);

    Layer layer2 = new Layer(psdImage);
    layer2.Name = "Layer 2";
    group2.AddLayer(layer2);

    Layer layer3 = new Layer(psdImage);
    layer3.Name = "Layer 3";
    group2.AddLayer(layer3);

    Layer layer4 = new Layer(psdImage);
    layer4.Name = "Layer 4";
    group1.AddLayer(layer4);

    psdImage.Save();
}
```

### انظر أيضًا

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


