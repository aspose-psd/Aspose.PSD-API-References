---
title: ShmdResource.SubResources
second_title: Aspose.PSD لمرجع .NET API
description: ShmdResource ملكية. يحصل على الموارد الفرعية لمورد shmd.
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

يحصل على الموارد الفرعية لمورد shmd.

```csharp
public LayerResource[] SubResources { get; }
```

### أمثلة

توضح التعليمة البرمجية التالية دعم مورد MlstResource الذي يوفر آلية منخفضة المستوى لمعالجة حالات الطبقة.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // تعطيل الطبقة 1 في الإطار 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### أنظر أيضا

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* المجسم [Aspose.PSD](../../../)


