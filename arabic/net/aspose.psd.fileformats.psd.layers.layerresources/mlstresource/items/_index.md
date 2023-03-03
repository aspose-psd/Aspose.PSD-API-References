---
title: MlstResource.Items
second_title: Aspose.PSD لمرجع .NET API
description: MlstResource ملكية. الحصول على الهياكل أو تعيينها.
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
## MlstResource.Items property

الحصول على الهياكل أو تعيينها.

```csharp
public OSTypeStructure[] Items { get; }
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

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../mlstresource/)
* المجسم [Aspose.PSD](../../../)


